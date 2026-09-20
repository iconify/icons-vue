<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceeknj_js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ceeknj_js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-211" /></template>
