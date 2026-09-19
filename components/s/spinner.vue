<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq88fx61h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sq88fx61h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:spinner" /></template>
