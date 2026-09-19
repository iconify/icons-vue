<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvzp7mbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xvzp7mbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pennant-1" /></template>
