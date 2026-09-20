<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g606jxbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g606jxbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:projector" /></template>
