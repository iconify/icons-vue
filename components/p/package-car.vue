<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/a/a9vsgkbga.css';
import '../../css/g/ghufp1bsu.css';
import '../../css/r/rr_rycfur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="a9vsgkbga"/><circle class="ghufp1bsu"/><path class="rr_rycfur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:package-car" /></template>
