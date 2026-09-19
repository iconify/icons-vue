<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up_ob0yqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="up_ob0yqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:piano" /></template>
