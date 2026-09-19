<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5-9h0xfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o5-9h0xfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:windy" /></template>
