<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7me47nlj.css';
import '../../css/r/ryesqkbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l7me47nlj"/><path class="ryesqkbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vegetation-height" /></template>
