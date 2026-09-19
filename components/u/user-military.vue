<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikuckebwq.css';
import '../../css/r/r1o9g9byu.css';
import '../../css/g/gad0czbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ikuckebwq"/><path class="r1o9g9byu"/><path class="gad0czbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-military" /></template>
