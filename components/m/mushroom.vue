<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrerf5bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrerf5bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mushroom" /></template>
