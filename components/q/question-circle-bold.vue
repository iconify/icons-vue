<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df1uvuf1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="df1uvuf1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:question-circle-bold" /></template>
