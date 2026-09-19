<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xea7kfdxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xea7kfdxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pennant-outline" /></template>
