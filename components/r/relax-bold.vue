<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xei7h-0er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xei7h-0er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:relax-bold" /></template>
