<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7__hwxfb.css';
import '../../css/f/fo40zs72w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u7__hwxfb"/><path class="fo40zs72w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-check" /></template>
