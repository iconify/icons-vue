<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iomp6lkyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iomp6lkyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:telegram" /></template>
