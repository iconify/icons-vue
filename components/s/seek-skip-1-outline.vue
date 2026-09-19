<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zddxcdb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zddxcdb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seek-skip-1-outline" /></template>
