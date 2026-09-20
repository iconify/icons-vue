<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mze16cbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mze16cbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sunglasses-sharp" /></template>
