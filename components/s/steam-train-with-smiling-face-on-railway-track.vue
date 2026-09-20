<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgxhaab5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mgxhaab5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:steam-train-with-smiling-face-on-railway-track" /></template>
