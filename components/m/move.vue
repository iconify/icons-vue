<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk4ocrbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk4ocrbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:move" /></template>
