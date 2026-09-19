<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5z7n2dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ft5z7n2dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:paste-outline" /></template>
