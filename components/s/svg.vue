<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns92qbcwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns92qbcwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:svg" /></template>
