<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/eypk3skau.css';
import '../../css/k/kf2q3hbnt.css';
import '../../css/p/pb4zwjt1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="eypk3skau"/><circle class="kf2q3hbnt"/><path class="pb4zwjt1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:spline" /></template>
