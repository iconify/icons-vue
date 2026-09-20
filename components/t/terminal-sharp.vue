<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3o1gwbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3o1gwbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:terminal-sharp" /></template>
