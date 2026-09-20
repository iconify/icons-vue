<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry9ol6lsh.css';
import '../../css/o/okcsfevjn.css';
import '../../css/w/wntb9b47b.css';
import '../../css/l/ld9cusbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ry9ol6lsh"><circle class="okcsfevjn"/><circle class="wntb9b47b"/><circle class="ld9cusbiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:varnish" /></template>
