<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/sboli8e2u.css';
import '../../css/o/opxuyt77v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="sboli8e2u"/><path class="opxuyt77v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shower-head" /></template>
