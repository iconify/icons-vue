<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/t/tnva5duer.css';
import '../../css/i/ixl6s1ssc.css';
import '../../css/z/zh84q581l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="tnva5duer"/><path class="ixl6s1ssc"/><path class="zh84q581l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mg-4x3" /></template>
