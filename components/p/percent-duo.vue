<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvom6-lkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kvom6-lkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:percent-duo" /></template>
