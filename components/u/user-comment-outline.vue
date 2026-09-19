<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xngcx7bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xngcx7bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:user-comment-outline" /></template>
