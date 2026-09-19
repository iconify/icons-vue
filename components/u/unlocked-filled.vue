<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm2cx4-yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bm2cx4-yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:unlocked-filled" /></template>
