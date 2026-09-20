<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4a6xubvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4a6xubvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:plug" /></template>
