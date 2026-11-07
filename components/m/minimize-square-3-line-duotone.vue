<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cn4_qkqch.css';
import '../../css/v/vv3m6lbyb.css';
import '../../css/y/yqghi_b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cn4_qkqch"/><path class="vv3m6lbyb"/><path class="yqghi_b_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-3-line-duotone" /></template>
