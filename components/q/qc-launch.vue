<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r482a7max.css';
import '../../css/k/kr-9jkbii.css';
import '../../css/i/iyzleyb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r482a7max"/><path class="kr-9jkbii"/><path class="iyzleyb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:qc-launch" /></template>
