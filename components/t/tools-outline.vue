<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu24x1v0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mu24x1v0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tools-outline" /></template>
