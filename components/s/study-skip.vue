<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvoqjmboh.css';
import '../../css/j/jdpi5byld.css';
import '../../css/m/mznjhlbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pvoqjmboh"/><path class="jdpi5byld"/><path class="mznjhlbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:study-skip" /></template>
