<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tun-vsp7b.css';
import '../../css/l/lb_uwtm7d.css';
import '../../css/g/gfwzmm8cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tun-vsp7b"/><path class="lb_uwtm7d"/><path class="gfwzmm8cw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-square-linear" /></template>
