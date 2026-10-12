<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul0vswbpp.css';
import '../../css/q/qggpi_b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ul0vswbpp"/><path class="qggpi_b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pencil-sparkle-stroke-20" /></template>
