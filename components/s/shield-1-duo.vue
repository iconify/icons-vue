<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnqrz6ssl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wnqrz6ssl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-1-duo" /></template>
