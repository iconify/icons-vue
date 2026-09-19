<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0nui7ith.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z0nui7ith"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wifi-50-outline" /></template>
