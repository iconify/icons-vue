<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8z10m13t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8z10m13t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:scissors-sharp" /></template>
