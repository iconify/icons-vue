<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb26wmb_b.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m09ey7kqu.css';
import '../../css/k/kltq48bze.css';
import '../../css/p/priikhbhb.css';
import '../../css/y/ym38t2bqf.css';
import '../../css/f/fndzf-b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb26wmb_b secondary"/><g class="dt0cm9dhy primary"><path class="m09ey7kqu"/><path class="kltq48bze"/><path class="priikhbhb"/><path class="ym38t2bqf"/><path class="fndzf-b4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:palette-duo" /></template>
