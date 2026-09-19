<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo2hszohb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="oo2hszohb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone-remove-outline" /></template>
