<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlbvg8bgk.css';
import '../../css/a/ax-mmibru.css';
import '../../css/v/vyx3_bcxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mlbvg8bgk"/><path class="ax-mmibru"/><path class="vyx3_bcxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sleet-20-bold" /></template>
