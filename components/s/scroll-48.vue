<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckj36vb5o.css';
import '../../css/t/tmqztg9xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ckj36vb5o"/><path class="tmqztg9xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scroll-48" /></template>
