<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeifo2b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="xeifo2b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-third-quarter" /></template>
