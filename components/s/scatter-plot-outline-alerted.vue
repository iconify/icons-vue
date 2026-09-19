<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmk6nb6wm.css';
import '../../css/s/s2jvy2blx.css';
import '../../css/g/gs0aklbvc.css';
import '../../css/j/jyuuws0ht.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bmk6nb6wm clr-i-outline--alerted clr-i-outline-path-1--alerted"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted s2jvy2blx"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted gs0aklbvc"/><path class="clr-i-outline--alerted clr-i-outline-path-4--alerted jyuuws0ht"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-5--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:scatter-plot-outline-alerted" /></template>
