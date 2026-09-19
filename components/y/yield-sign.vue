<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grvmhoowa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="grvmhoowa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:yield-sign" /></template>
