<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2hxwibdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p2hxwibdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mouse-pointer-outline" /></template>
