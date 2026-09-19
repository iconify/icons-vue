<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t413p727r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t413p727r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen" /></template>
