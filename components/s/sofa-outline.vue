<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg8h_74nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yg8h_74nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sofa-outline" /></template>
