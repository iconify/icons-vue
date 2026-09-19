<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkkna6b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pkkna6b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-exclamation-bold" /></template>
