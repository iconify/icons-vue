<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb1pp9-sc.css';
import '../../css/d/dk5r3ibbf.css';
import '../../css/p/poi27mi1l.css';
import '../../css/a/aomh9ccmy.css';
import '../../css/y/yi_k3xgwx.css';
import '../../css/y/y-p-w8zqg.css';
import '../../css/t/tbdf0p_su.css';
import '../../css/e/ebw105bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zb1pp9-sc"/><path class="dk5r3ibbf"/><path class="poi27mi1l"/><path class="aomh9ccmy"/><path class="yi_k3xgwx"/><path class="y-p-w8zqg"/><path class="tbdf0p_su"/><path class="ebw105bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oracle-apex-light" /></template>
