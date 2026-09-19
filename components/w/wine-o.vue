<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yccvg5xel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1120,"height":2208};
const content = `<path class="yccvg5xel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:wine-o" /></template>
