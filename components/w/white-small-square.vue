<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztj20xrrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ztj20xrrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-small-square" /></template>
