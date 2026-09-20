<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp6l-5t5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lp6l-5t5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:spiral-shape" /></template>
