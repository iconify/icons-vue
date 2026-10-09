<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8_piicxj.css';
import '../../css/h/ht9oo05-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u8_piicxj"/><path class="ht9oo05-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:receipt-20-bold" /></template>
