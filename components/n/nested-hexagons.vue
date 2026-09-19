<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw8evbciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uw8evbciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nested-hexagons" /></template>
