<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd4gsf7oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zd4gsf7oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-1-outline" /></template>
