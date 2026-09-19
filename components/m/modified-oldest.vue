<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0g_v6b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l0g_v6b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:modified-oldest" /></template>
