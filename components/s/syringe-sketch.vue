<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w2mn3losm.css';
import '../../css/s/skq03ibah.css';
import '../../css/l/l1i4c7ymy.css';
import '../../css/e/elu64db-k.css';
import '../../css/h/h38x_m0_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w2mn3losm"/><path class="skq03ibah wm-k"/><path class="l1i4c7ymy wm-a"/><path class="elu64db-k wm-k"/><path class="h38x_m0_y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:syringe-sketch" /></template>
