<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/std_354_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="std_354_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:zero-outline" /></template>
