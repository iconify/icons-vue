<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxh3-5bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxh3-5bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reply" /></template>
