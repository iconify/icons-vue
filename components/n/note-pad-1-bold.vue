<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zweq5cbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zweq5cbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-pad-1-bold" /></template>
