<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2d_nybeh.css';
import '../../css/t/taasc_mln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2d_nybeh"/><path class="taasc_mln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zoom-out" /></template>
