<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rujow35iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rujow35iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:monitor-lock" /></template>
