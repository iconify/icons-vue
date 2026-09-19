<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frzz74bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="frzz74bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:storm" /></template>
