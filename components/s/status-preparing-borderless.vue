<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/z9edi6b_u.css';
import '../../css/k/kd06ylh6g.css';
import '../../css/e/einsz8zxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><circle class="z9edi6b_u"/><circle class="kd06ylh6g"/><circle class="einsz8zxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-preparing-borderless" /></template>
