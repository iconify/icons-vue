<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6khetxdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x6khetxdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-map-pin-with-dot" /></template>
