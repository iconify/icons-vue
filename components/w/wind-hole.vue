<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlbdts9qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rlbdts9qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wind-hole" /></template>
