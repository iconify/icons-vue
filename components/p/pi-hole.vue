<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiyy8_k4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiyy8_k4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pi-hole" /></template>
