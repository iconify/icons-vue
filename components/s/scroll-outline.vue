<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iooj79bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="iooj79bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scroll-outline" /></template>
