<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx4zb4yjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jx4zb4yjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:toolbox" /></template>
