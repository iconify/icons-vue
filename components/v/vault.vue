<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/n1tta3b2f.css';
import '../../css/e/eruig_ygc.css';
import '../../css/k/kmfuvw0ir.css';
import '../../css/i/iu3w7gbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="n1tta3b2f"/><path class="eruig_ygc"/><circle class="kmfuvw0ir"/><path class="iu3w7gbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:vault" /></template>
