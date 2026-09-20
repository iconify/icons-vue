<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tug4i0euj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tug4i0euj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:youtube" /></template>
