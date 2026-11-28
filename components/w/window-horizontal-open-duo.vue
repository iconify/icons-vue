<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgdk03bfh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f6c2tj9bn.css';
import '../../css/r/r1j2eicsi.css';
import '../../css/c/cfk_ovbga.css';
import '../../css/o/og8zkpbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgdk03bfh secondary"/><g class="dt0cm9dhy primary"><path class="f6c2tj9bn"/><path class="r1j2eicsi"/><path class="cfk_ovbga"/><path class="og8zkpbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:window-horizontal-open-duo" /></template>
