<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7lu8lw2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":83.196};
const content = `<path class="r7lu8lw2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vudu" /></template>
