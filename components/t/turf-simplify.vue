<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbskly18j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bbskly18j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-simplify" /></template>
