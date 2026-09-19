<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzuvhhb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zzuvhhb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sparkles" /></template>
