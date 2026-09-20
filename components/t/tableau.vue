<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw083vbat.css';
import '../../css/e/e_zb-7beo.css';
import '../../css/t/t06aricwk.css';
import '../../css/q/qah69vldv.css';
import '../../css/u/ukjnooizv.css';
import '../../css/k/k1byq0bvi.css';
import '../../css/q/qji9niyta.css';
import '../../css/c/c_-m2p8sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="fw083vbat"/><path class="e_zb-7beo"/><path class="t06aricwk"/><path class="qah69vldv"/><path class="ukjnooizv"/><path class="k1byq0bvi"/><path clip-rule="evenodd" class="qji9niyta"/><path class="c_-m2p8sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tableau" /></template>
