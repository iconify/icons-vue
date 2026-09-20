<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uee3w3bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="uee3w3bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waxing-crescent-1" /></template>
