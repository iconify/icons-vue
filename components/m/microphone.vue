<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0z3-vbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p0z3-vbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:microphone" /></template>
