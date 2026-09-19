<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2wgzk62w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="u2wgzk62w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:z-square" /></template>
