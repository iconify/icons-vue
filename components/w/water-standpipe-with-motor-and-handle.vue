<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssfczzjcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ssfczzjcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-standpipe-with-motor-and-handle" /></template>
