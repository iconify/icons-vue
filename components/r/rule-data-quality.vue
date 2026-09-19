<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6zcjhb8g.css';
import '../../css/v/vt3ssfbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j6zcjhb8g"/><path class="vt3ssfbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-data-quality" /></template>
