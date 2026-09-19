<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy85065lx.css';
import '../../css/u/u7sjykb1e.css';
import '../../css/o/onyqr8g1f.css';
import '../../css/y/yei7kmfgc.css';
import '../../css/t/tii6inn6s.css';
import '../../css/u/u1bmbxbnh.css';
import '../../css/c/chmcmpb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gy85065lx"/><path class="u7sjykb1e"/><path class="onyqr8g1f"/><path class="yei7kmfgc"/><path class="tii6inn6s"/><path class="u1bmbxbnh"/><path class="chmcmpb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:sk-1x1" /></template>
