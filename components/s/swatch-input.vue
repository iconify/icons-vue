<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_xxphbqx.css';
import '../../css/r/r0tjoehii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="y_xxphbqx"/><rect class="ouiSwatchInput__stroke r0tjoehii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:swatch-input" /></template>
