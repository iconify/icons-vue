<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mit5f8bas.css';
import '../../css/e/ek_6wsbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mit5f8bas"/><path class="ek_6wsbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rain-heavy" /></template>
