<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3ytnwbhg.css';
import '../../css/o/o89w-k64d.css';
import '../../css/c/c9uy2uufm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v3ytnwbhg"/><path class="o89w-k64d"/><path class="c9uy2uufm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tile-20-bold" /></template>
