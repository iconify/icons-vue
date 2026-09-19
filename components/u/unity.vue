<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y28_cgdgv.css';
import '../../css/d/d26v317vg.css';
import '../../css/l/l2qa26fpr.css';
import '../../css/l/leg57pb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="y28_cgdgv"/><g class="d26v317vg"><path class="l2qa26fpr"/><path class="leg57pb1f"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:unity" /></template>
