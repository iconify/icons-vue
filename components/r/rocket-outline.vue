<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnz88h8pe.css';
import '../../css/v/vs_irilvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pnz88h8pe"/><path class="vs_irilvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:rocket-outline" /></template>
