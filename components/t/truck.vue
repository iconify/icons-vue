<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yzik_ib5f.css';
import '../../css/h/heyab7big.css';
import '../../css/p/pfdln_tgy.css';
import '../../css/o/o4zzqkbgz.css';
import '../../css/m/mz6m6-b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="yzik_ib5f"/><path clip-rule="evenodd" class="heyab7big"/><path class="pfdln_tgy"/><path clip-rule="evenodd" class="o4zzqkbgz"/><path class="mz6m6-b7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:truck" /></template>
