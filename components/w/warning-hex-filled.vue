<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fppk0pz3y.css';
import '../../css/z/zay7feb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fppk0pz3y"/><path class="zay7feb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-hex-filled" /></template>
