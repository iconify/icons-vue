<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/kyr7bmvnc.css';
import '../../css/w/wr92o1bsm.css';
import '../../css/a/aur6p6i1v.css';
import '../../css/s/sfizj6b7w.css';
import '../../css/m/mkn098bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="kyr7bmvnc wm-deco"/><path class="wm-deco wr92o1bsm"/><path class="aur6p6i1v wm-k"/><path class="sfizj6b7w wm-a"/><path class="mkn098bws wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pencil-ruler-blueprint" /></template>
