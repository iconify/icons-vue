<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_2cp-b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c_2cp-b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:skull-1-bold" /></template>
