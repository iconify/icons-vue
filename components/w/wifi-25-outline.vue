<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wye1bdb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wye1bdb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wifi-25-outline" /></template>
