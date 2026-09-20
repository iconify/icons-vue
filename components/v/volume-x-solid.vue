<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em-2je60d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em-2je60d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:volume-x-solid" /></template>
