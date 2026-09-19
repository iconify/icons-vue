<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up3xwf3il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="up3xwf3il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:regular-shape-o" /></template>
