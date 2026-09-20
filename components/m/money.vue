<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk-fxejkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk-fxejkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:money" /></template>
