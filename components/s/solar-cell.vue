<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i24gx0b8d.css';
import '../../css/r/rnqc0wxrk.css';
import '../../css/j/jmpiblj0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="i24gx0b8d"/><path class="rnqc0wxrk"/><path class="jmpiblj0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:solar-cell" /></template>
