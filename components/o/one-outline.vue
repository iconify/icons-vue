<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm-vvbm1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jm-vvbm1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:one-outline" /></template>
