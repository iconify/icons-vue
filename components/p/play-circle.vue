<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1rfbccbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f1rfbccbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:play-circle" /></template>
