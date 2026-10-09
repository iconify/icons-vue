<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy6gx925n.css';
import '../../css/m/mralpzb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fy6gx925n"/><path class="mralpzb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-20" /></template>
