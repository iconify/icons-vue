<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c35gnuhtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="c35gnuhtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-721" /></template>
