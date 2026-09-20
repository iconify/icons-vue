<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx40f8buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx40f8buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:pen-square" /></template>
