<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdidh17-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rdidh17-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:zero-duo" /></template>
