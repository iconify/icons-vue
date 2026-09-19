<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t31v27vgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="t31v27vgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:proj-conic" /></template>
