<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc61z9lrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kc61z9lrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wrench-bold" /></template>
