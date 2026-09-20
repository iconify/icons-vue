<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd6863zjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="yd6863zjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:zoom-in" /></template>
