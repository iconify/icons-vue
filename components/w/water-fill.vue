<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc75c6viz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="uc75c6viz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:water-fill" /></template>
