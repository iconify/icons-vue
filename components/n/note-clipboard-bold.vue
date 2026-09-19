<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7zw--b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="u7zw--b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-clipboard-bold" /></template>
