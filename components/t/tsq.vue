<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci-bfktii.css';
import '../../css/j/j01m1nbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ci-bfktii"/><path class="j01m1nbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tsq" /></template>
