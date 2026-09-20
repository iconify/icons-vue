<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtnihcb_h.css';
import '../../css/l/lgq_fxbzk.css';
import '../../css/u/uwrfz6bek.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/j/j0pbotpte.css';
import '../../css/a/a0bafb29g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qtnihcb_h"/><path class="lgq_fxbzk"/><path class="uwrfz6bek"/><g class="ij2x_72vy"><path class="j0pbotpte"/><path class="a0bafb29g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:scroll-horizontal" /></template>
