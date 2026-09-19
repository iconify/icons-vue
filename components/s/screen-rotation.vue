<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyrmdsbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oyrmdsbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:screen-rotation" /></template>
