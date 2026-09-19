<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx_5pr5ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tx_5pr5ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-75" /></template>
