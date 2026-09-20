<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f81fp6svz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f81fp6svz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:siren-off" /></template>
