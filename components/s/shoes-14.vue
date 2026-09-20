<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uohix1b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uohix1b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:shoes-14" /></template>
