<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxdvh4q1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fxdvh4q1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:voice-scan-2-solid" /></template>
