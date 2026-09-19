<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5ig-ib6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i5ig-ib6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:play" /></template>
