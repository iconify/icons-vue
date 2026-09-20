<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il_najbxg.css';
import '../../css/n/n1lsf0bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<defs><path id="SVG2jlUvrhl" class="il_najbxg"/></defs><g clip-rule="evenodd" class="n1lsf0bnc"><use href="#SVG2jlUvrhl"/><use href="#SVG2jlUvrhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:send-filled" /></template>
