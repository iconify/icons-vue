<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgu8nmfrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wgu8nmfrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:switcher" /></template>
