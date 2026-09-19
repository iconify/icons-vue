<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/binaknbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="binaknbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seven" /></template>
