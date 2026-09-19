<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct_xoybyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ct_xoybyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shovel" /></template>
