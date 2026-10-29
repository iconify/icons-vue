<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n060wrb-o.css';
import '../../css/v/vexbc1b_g.css';
import '../../css/j/j6xpl_b5y.css';
import '../../css/b/bfklh_btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n060wrb-o wm-k"/><path class="vexbc1b_g wm-a"/><path class="j6xpl_b5y wm-k"/><path class="bfklh_btr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microscope-sketch" /></template>
