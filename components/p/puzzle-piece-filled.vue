<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfvc8y0xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfvc8y0xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:puzzle-piece-filled" /></template>
