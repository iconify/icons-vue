<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hao-y3_km.css';
import '../../css/s/siiu_ybwm.css';
import '../../css/p/ptrg_gs-t.css';
import '../../css/i/imlf68b1a.css';
import '../../css/w/wi89-ibup.css';
import '../../css/f/frr9dj5ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hao-y3_km"/><path class="siiu_ybwm"/><path class="ptrg_gs-t"/><path class="imlf68b1a"/><path class="wi89-ibup"/><path class="frr9dj5ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:window-frame-bold-duotone" /></template>
