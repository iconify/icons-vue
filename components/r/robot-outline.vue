<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afyoo0b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="afyoo0b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:robot-outline" /></template>
