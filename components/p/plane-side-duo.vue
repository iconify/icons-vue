<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4rvo_b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b4rvo_b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plane-side-duo" /></template>
