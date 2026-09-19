<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyn9yi1sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yyn9yi1sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:squircle-outline" /></template>
