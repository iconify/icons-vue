<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-nfqwbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e-nfqwbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seek-step-outline" /></template>
