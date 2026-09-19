<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt1hw8ngl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nt1hw8ngl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:strikethrough-bold" /></template>
