<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq9f_m1cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq9f_m1cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:play" /></template>
