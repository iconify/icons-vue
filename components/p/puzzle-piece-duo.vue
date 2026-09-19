<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4gcxe4mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x4gcxe4mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:puzzle-piece-duo" /></template>
