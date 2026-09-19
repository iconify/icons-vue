<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taasc_mln.css';
import '../../css/e/eu8t76b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="taasc_mln"/><path class="eu8t76b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zoom-fit" /></template>
