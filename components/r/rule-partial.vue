<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciqspz6bd.css';
import '../../css/v/v_ge03b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ciqspz6bd"/><path class="v_ge03b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-partial" /></template>
