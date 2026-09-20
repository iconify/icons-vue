<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij1w0bbue.css';
import '../../css/q/qsovutbiq.css';
import '../../css/e/e_raf5bng.css';
import '../../css/d/dbe1d0bnt.css';
import '../../css/c/cw1nr3o_g.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/u/urifjtb8z.css';
import '../../css/f/fueg03b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="ij1w0bbue"/><path class="qsovutbiq"/><g class="e_raf5bng"><path class="dbe1d0bnt"/><path class="cw1nr3o_g"/></g><g class="brzn_0bpr"><ellipse class="urifjtb8z"/><path class="fueg03b6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:roasted-coffee-bean" /></template>
