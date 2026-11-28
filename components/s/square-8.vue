<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyf-vcdxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyf-vcdxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-8" /></template>
