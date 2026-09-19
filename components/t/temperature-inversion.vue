<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww9l4w97m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ww9l4w97m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-inversion" /></template>
