<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rnxt--b2x.css';
import '../../css/k/knraakbcn.css';
import '../../css/b/bhedg2bcn.css';
import '../../css/o/opankvl_l.css';
import '../../css/r/r3n5semei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rnxt--b2x wm-k"/><path class="knraakbcn wm-shine"/><path class="bhedg2bcn wm-shine"/><path class="opankvl_l wm-shine"/><path class="r3n5semei wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:sticky-note" /></template>
