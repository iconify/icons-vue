<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k4wwxhbyk.css';
import '../../css/k/kh-rtibce.css';
import '../../css/i/i3f2j6b_u.css';
import '../../css/e/evvy2i13i.css';
import '../../css/p/povs420wf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGND39NeLo"><g class="ft5dv1b6b"><path class="k4wwxhbyk"/><path class="kh-rtibce"/><circle class="i3f2j6b_u"/><circle class="evvy2i13i"/><circle class="povs420wf"/></g></mask></defs><path mask="url(#SVGND39NeLo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tickets-two" /></template>
