<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy52vvbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy52vvbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:share" /></template>
