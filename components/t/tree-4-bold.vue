<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk0f0oa3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qk0f0oa3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-4-bold" /></template>
