<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_q5cxbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="d_q5cxbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:truck-medical" /></template>
