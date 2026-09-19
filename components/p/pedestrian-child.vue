<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6x13_b1f.css';
import '../../css/j/jupyvy7ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6x13_b1f"/><path class="jupyvy7ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pedestrian-child" /></template>
