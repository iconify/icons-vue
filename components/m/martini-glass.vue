<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erxx7vbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erxx7vbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:martini-glass" /></template>
