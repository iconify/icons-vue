<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1c9zmbsp.css';
import '../../css/l/lwy4_6bpt.css';
import '../../css/e/ex7ic0gtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f1c9zmbsp"/><path class="lwy4_6bpt"/><path class="ex7ic0gtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-down-20-bold" /></template>
