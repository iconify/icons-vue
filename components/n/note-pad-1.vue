<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpmc3ybxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mpmc3ybxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-pad-1" /></template>
