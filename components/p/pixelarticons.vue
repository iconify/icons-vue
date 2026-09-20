<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7qcs1agw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7qcs1agw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:pixelarticons" /></template>
