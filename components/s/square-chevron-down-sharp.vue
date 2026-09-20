<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex7adytcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex7adytcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-chevron-down-sharp" /></template>
