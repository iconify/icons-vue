<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1l4rc0mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1l4rc0mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:user-x" /></template>
