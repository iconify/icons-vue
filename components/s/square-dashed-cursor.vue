<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk-a-0bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk-a-0bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-dashed-cursor" /></template>
