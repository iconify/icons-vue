<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6aiztlet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":464};
const content = `<path class="y6aiztlet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:rotate-ccw" /></template>
