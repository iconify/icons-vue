<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swiw1cbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="swiw1cbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:modulo-duo" /></template>
