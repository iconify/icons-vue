<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rmc1u9j4i.css';
import '../../css/o/om4lnzbpu.css';
import '../../css/y/yg_stwb0g.css';
import '../../css/c/c0piegl7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rmc1u9j4i"/><path class="om4lnzbpu"/><path class="yg_stwb0g"/><path class="c0piegl7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-minimalistic-input-linear" /></template>
