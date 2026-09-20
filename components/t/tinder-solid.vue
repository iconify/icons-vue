<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us6dxlbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="us6dxlbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tinder-solid" /></template>
