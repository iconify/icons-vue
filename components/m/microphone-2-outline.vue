<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-5yzob-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l-5yzob-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:microphone-2-outline" /></template>
