<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm0wchruk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wm0wchruk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-1" /></template>
