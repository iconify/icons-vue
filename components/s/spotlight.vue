<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uge_j_b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uge_j_b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:spotlight" /></template>
