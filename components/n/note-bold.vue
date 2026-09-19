<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1zgeubyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="x1zgeubyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-bold" /></template>
