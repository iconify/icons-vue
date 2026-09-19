<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2d2pp2dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s2d2pp2dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:plane-sea" /></template>
