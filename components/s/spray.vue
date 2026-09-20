<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk1z5mbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk1z5mbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:spray" /></template>
