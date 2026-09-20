<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co913ybrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="co913ybrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:refresh" /></template>
