<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb731ubzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xb731ubzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:yield-sign-duo" /></template>
