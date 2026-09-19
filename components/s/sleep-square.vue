<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-8f7s1ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="y-8f7s1ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sleep-square" /></template>
