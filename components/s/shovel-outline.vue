<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnn7sfq2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nnn7sfq2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shovel-outline" /></template>
