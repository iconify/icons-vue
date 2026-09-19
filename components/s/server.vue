<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fezqsmbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fezqsmbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:server" /></template>
