<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm_kd6_tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lm_kd6_tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rain-scattered-night" /></template>
