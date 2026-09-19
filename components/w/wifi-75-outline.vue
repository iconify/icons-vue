<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou4kbz7is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ou4kbz7is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wifi-75-outline" /></template>
