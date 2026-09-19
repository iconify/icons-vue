<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxj823l5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mxj823l5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:vaccination" /></template>
