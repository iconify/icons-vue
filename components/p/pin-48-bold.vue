<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy-rofhks.css';
import '../../css/u/uzpb98bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vy-rofhks"/><path class="uzpb98bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pin-48-bold" /></template>
