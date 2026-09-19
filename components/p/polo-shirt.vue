<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2wgblbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2wgblbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:polo-shirt" /></template>
