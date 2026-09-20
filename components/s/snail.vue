<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf34dzvmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf34dzvmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:snail" /></template>
