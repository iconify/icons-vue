<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opms00cru.css';
import '../../css/i/i-ss3sbvd.css';
import '../../css/u/utwu3pj0d.css';
import '../../css/r/rb1la7bok.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/r/r1hnq_b_z.css';
import '../../css/k/knqbvab_e.css';
import '../../css/g/gvu-qrbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="opms00cru"/><path class="i-ss3sbvd"/><path class="utwu3pj0d"/><path class="rb1la7bok"/><g class="brzn_0bpr"><path class="r1hnq_b_z"/><path class="knqbvab_e"/><path class="gvu-qrbrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mechanical-leg" /></template>
