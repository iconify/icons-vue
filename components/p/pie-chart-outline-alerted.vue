<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmk6nb6wm.css';
import '../../css/e/e-y7gmbcx.css';
import '../../css/h/hppu_rtzq.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bmk6nb6wm clr-i-outline--alerted clr-i-outline-path-1--alerted"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted e-y7gmbcx"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted hppu_rtzq"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:pie-chart-outline-alerted" /></template>
