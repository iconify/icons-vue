<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz5dxrb9c.css';
import '../../css/d/dv49fzpdk.css';
import '../../css/k/kiarm54_m.css';
import '../../css/d/doj9dq_jg.css';
import '../../css/h/hjtdfnrch.css';
import '../../css/e/ehj3mcm7x.css';
import '../../css/z/zrz3ievtm.css';
import '../../css/k/kswnx2b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="sz5dxrb9c"/><path class="dv49fzpdk"/><path class="kiarm54_m"/><g class="doj9dq_jg"><path class="hjtdfnrch"/><path class="ehj3mcm7x"/><path class="zrz3ievtm"/><path class="kswnx2b7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:owl" /></template>
