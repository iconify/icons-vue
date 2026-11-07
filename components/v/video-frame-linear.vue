<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvjk-cbox.css';
import '../../css/r/r_0pl6b2k.css';
import '../../css/t/txon6o65c.css';
import '../../css/u/uhck3lx6y.css';
import '../../css/d/d7k56tgtd.css';
import '../../css/y/yirxaabex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="r_0pl6b2k"/><path class="txon6o65c"/><path class="uhck3lx6y"/><path class="d7k56tgtd"/><path class="yirxaabex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-linear" /></template>
