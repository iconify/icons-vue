<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe94j3tcg.css';
import '../../css/u/u-hablz3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oe94j3tcg"/><path class="u-hablz3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:succession" /></template>
