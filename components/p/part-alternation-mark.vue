<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-3fxs8ew.css';
import '../../css/y/yhn66eyul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="p-3fxs8ew"/><path class="yhn66eyul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:part-alternation-mark" /></template>
