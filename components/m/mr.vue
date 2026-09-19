<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/r/rjkm9-bua.css';
import '../../css/o/oz6e2q1oa.css';
import '../../css/y/y5u-3acwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="rjkm9-bua"/><path class="oz6e2q1oa"/><path class="y5u-3acwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:mr" /></template>
