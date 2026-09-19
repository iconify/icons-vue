<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg00pobiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hg00pobiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:palette-bold" /></template>
