<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zr1w2ccln.css';
import '../../css/m/m5hxkk2rn.css';
import '../../css/s/shbmdrbdo.css';
import '../../css/q/q7huiowpz.css';
import '../../css/l/losrkpbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><ellipse class="zr1w2ccln"/><circle class="m5hxkk2rn"/><circle class="shbmdrbdo"/><circle class="q7huiowpz"/><path class="losrkpbin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rabbit" /></template>
