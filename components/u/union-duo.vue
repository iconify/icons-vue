<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx6lrpb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bx6lrpb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:union-duo" /></template>
