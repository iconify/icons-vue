<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm8gi1btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cm8gi1btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:octagon" /></template>
