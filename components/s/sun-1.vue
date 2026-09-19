<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdicp7lrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jdicp7lrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sun-1" /></template>
