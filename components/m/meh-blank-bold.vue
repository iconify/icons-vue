<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j02izstjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="j02izstjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:meh-blank-bold" /></template>
