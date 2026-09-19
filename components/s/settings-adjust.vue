<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx4_2tenc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bx4_2tenc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:settings-adjust" /></template>
