<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2tew1o-z.css';
import '../../css/c/cp8_n08jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y2tew1o-z"/><path class="cp8_n08jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:receipt" /></template>
