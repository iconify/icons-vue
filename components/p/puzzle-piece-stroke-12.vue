<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhc7mbtcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rhc7mbtcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:puzzle-piece-stroke-12" /></template>
