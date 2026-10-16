<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1z3abb-w.css';
import '../../css/h/h2w2gxl4v.css';
import '../../css/m/mg0mcnb8n.css';
import '../../css/i/i2ko5wydq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h1z3abb-w"/><path class="h2w2gxl4v"/><path class="mg0mcnb8n"/><path class="i2ko5wydq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shed-48-bold" /></template>
