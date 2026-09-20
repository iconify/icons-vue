<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-9m9rnsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-9m9rnsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-align-right-box" /></template>
