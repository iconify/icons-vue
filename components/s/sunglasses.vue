<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyr36-bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyr36-bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sunglasses" /></template>
