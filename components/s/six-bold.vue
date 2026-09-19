<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo38sygpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bo38sygpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:six-bold" /></template>
