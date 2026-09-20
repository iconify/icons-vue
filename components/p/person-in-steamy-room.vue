<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sldhzzaim.css';
import '../../css/o/one5r5chc.css';
import '../../css/e/em2ouxbpy.css';
import '../../css/s/safse3bij.css';
import '../../css/n/nxj8h-n6y.css';
import '../../css/m/m3knh5bgd.css';
import '../../css/g/gxexhxplj.css';
import '../../css/e/e26lxk8vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="sldhzzaim"/><path class="one5r5chc"/><path class="em2ouxbpy"/><path class="safse3bij"/><path class="nxj8h-n6y"/><path class="m3knh5bgd"/><path class="gxexhxplj"/><path class="e26lxk8vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-in-steamy-room" /></template>
