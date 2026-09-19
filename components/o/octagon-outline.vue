<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up3_59bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="up3_59bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:octagon-outline" /></template>
