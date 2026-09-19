<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wayyz3edj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="wayyz3edj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:multiply" /></template>
