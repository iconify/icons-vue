<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qto8aqbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qto8aqbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:pc-case" /></template>
