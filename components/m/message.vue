<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi2vt_c1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi2vt_c1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message" /></template>
