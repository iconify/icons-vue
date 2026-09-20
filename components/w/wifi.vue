<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zat7oigab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zat7oigab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:wifi" /></template>
