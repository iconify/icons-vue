<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx8vpfx_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="cx8vpfx_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-above-text" /></template>
