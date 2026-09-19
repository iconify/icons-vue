<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm04t4mmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fm04t4mmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:running-outline" /></template>
