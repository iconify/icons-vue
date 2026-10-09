<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-nxg9bwf.css';
import '../../css/u/u5r5zmbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-nxg9bwf"/><path class="u5r5zmbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refinery-20-bold" /></template>
