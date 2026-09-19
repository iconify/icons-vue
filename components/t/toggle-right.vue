<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru0o-1bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(1536 0) scale(-1 1)"><path class="ru0o-1bas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:toggle-right" /></template>
