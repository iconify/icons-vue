<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j7610ybth.css';
import '../../css/f/f5a14lz8y.css';
import '../../css/o/oufyqczij.css';
import '../../css/v/vaqayeb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="j7610ybth"/><path class="f5a14lz8y"/><path class="oufyqczij"/><path clip-rule="evenodd" class="vaqayeb5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:soccer-ball" /></template>
