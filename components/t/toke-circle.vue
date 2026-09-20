<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tov7z5b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tov7z5b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:toke-circle" /></template>
