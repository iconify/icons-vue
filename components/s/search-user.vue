<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmtvy7mvf.css';
import '../../css/l/l-3p4vbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fmtvy7mvf"/><path class="l-3p4vbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:search-user" /></template>
