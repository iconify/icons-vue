<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyfntu4cb.css';
import '../../css/r/ryn9fxb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kyfntu4cb"/><path class="ryn9fxb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-horizontal-20" /></template>
