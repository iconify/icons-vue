<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb-9lm2dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-9lm2dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:robot-face-sad-sharp" /></template>
