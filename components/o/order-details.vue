<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrcs4ql7k.css';
import '../../css/p/pfm1z1-ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wrcs4ql7k"/><path class="pfm1z1-ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:order-details" /></template>
