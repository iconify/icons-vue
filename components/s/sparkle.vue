<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo33xm2jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo33xm2jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sparkle" /></template>
