<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wh0_olksw.css';
import '../../css/n/np1e_hbeg.css';
import '../../css/b/b_90hnbhs.css';
import '../../css/d/daf6h8b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="wh0_olksw"/><circle transform="matrix(-1 0 0 1 17.492 4)" class="np1e_hbeg"/><circle class="b_90hnbhs"/><circle transform="matrix(-1 0 0 1 21.992 9)" class="np1e_hbeg"/><path class="daf6h8b0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paw-print" /></template>
