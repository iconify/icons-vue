<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiumi-d3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iiumi-d3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mid-summit" /></template>
