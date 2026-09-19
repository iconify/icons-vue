<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z10gtnb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z10gtnb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:watch-1-outline" /></template>
