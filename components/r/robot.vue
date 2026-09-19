<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/n2u8ozbbq.css';
import '../../css/y/y-qb6bbqh.css';
import '../../css/m/mybdgyglo.css';
import '../../css/t/t1x3gbbjf.css';
import '../../css/i/i8afg8uqh.css';
import '../../css/c/csyqkzb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="n2u8ozbbq"/><path class="y-qb6bbqh"/><circle class="mybdgyglo"/><circle class="t1x3gbbjf"/><rect class="i8afg8uqh"/><path class="csyqkzb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:robot" /></template>
