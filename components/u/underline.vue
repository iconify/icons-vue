<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl7hvkm3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vl7hvkm3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:underline" /></template>
