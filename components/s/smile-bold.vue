<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvg5shb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jvg5shb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:smile-bold" /></template>
