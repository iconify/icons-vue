<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8px1im5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y8px1im5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:spa-outline" /></template>
