<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ykfcbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n9ykfcbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underfloor-heating-20-bold" /></template>
