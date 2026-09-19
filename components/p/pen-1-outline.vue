<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxhr-mo1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qxhr-mo1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-1-outline" /></template>
