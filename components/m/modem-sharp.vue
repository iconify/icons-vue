<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cecxa5ukj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cecxa5ukj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:modem-sharp" /></template>
