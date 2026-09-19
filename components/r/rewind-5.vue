<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrndicbcc.css';
import '../../css/a/a8h6erbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mrndicbcc"/><path class="a8h6erbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rewind-5" /></template>
