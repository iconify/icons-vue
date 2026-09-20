<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi36m5bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zi36m5bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:symbol-1" /></template>
