<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3x1tqwwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f3x1tqwwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:up-right-from-square" /></template>
