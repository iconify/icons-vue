<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl6ttu2ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hl6ttu2ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plane-circle-exclamation" /></template>
