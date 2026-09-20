<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtuynmb0p.css';
import '../../css/g/ggq26fb1j.css';
import '../../css/i/i79gkzbce.css';
import '../../css/r/rk9p1tbyk.css';
import '../../css/s/scb2aub2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtuynmb0p"/><path class="ggq26fb1j"/><circle class="i79gkzbce"/><path class="rk9p1tbyk"/><path class="scb2aub2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:sanitizer" /></template>
