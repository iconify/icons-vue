<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh0oeyevc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rh0oeyevc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:watch-2-outline" /></template>
