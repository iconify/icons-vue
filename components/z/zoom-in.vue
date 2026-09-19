<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvsnzr3ef.css';
import '../../css/t/taasc_mln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qvsnzr3ef"/><path class="taasc_mln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zoom-in" /></template>
