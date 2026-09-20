<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otfa01r4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otfa01r4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-chevron-up" /></template>
