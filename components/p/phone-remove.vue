<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frk4m0bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="frk4m0bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone-remove" /></template>
