<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz6gfd7vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nz6gfd7vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-1-outline" /></template>
