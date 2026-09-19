<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igd-zybig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="igd-zybig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scissors-outline" /></template>
