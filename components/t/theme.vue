<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmin5_pxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rmin5_pxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:theme" /></template>
