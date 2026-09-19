<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axs82db6h.css';
import '../../css/d/d1z03cbds.css';
import '../../css/t/tjlr-ybbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="axs82db6h"/><path class="d1z03cbds"/><path class="tjlr-ybbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pointer-text" /></template>
