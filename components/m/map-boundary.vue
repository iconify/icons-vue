<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8u4d0zwp.css';
import '../../css/m/ms064kbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i8u4d0zwp"/><path class="ms064kbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:map-boundary" /></template>
