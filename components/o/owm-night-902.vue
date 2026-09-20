<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw45ad8_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="xw45ad8_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-902" /></template>
