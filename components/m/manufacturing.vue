<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_js2bbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d_js2bbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:manufacturing" /></template>
