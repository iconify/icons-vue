<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijm19vbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ijm19vbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:paperclip-outline" /></template>
