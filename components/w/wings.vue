<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/budxb8tgx.css';
import '../../css/d/d26v317vg.css';
import '../../css/v/v1osumnlh.css';
import '../../css/m/m04k14b0z.css';
import '../../css/t/t-qe7ekev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="budxb8tgx"/><g class="d26v317vg"><path class="v1osumnlh"/><path class="m04k14b0z"/><path class="t-qe7ekev"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:wings" /></template>
