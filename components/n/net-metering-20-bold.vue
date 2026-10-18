<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3cdfdc7r.css';
import '../../css/h/hhu4-ib3s.css';
import '../../css/l/l1yyp3cyj.css';
import '../../css/x/xv00olu6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3cdfdc7r"/><path class="hhu4-ib3s"/><path class="l1yyp3cyj"/><path class="xv00olu6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:net-metering-20-bold" /></template>
