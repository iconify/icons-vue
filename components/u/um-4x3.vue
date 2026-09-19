<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lugbcbdit.css';
import '../../css/n/n-5zhebym.css';
import '../../css/o/o3p8_abkq.css';
import '../../css/a/akwx2u1sy.css';
import '../../css/g/gp89tkdrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="lugbcbdit"/><path class="n-5zhebym"/><path class="o3p8_abkq"/><marker id="SVGEq3dreKJ" markerHeight="30" markerWidth="30"><path class="akwx2u1sy"/></marker><path marker-mid="url(#SVGEq3dreKJ)" class="gp89tkdrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:um-4x3" /></template>
