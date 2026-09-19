<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c73jm9scg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c73jm9scg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-3-bold" /></template>
