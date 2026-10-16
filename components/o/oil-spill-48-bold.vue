<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpi-8x__k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fpi-8x__k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-spill-48-bold" /></template>
