<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_ghm2b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="c_ghm2b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:volume-duo" /></template>
