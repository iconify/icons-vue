<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8x0ib4bs.css';
import '../../css/v/vjnfcfbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h8x0ib4bs"/><path class="vjnfcfbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:redo-20-bold" /></template>
