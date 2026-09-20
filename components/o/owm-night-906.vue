<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2c1qrbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="y2c1qrbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-906" /></template>
