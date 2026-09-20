<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lerkp7hns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lerkp7hns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:power-off" /></template>
