<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqubd6bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kqubd6bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pill-bold" /></template>
