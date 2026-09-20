<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aegt__b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aegt__b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-power-sharp" /></template>
