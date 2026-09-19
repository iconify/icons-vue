<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baq4hj58q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="baq4hj58q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:send-duo" /></template>
