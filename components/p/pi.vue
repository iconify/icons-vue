<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-g3u60ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-g3u60ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pi" /></template>
