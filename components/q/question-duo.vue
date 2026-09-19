<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wte0abq2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wte0abq2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:question-duo" /></template>
