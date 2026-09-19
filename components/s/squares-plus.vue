<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5omkxb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5omkxb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:squares-plus" /></template>
