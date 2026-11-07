<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t_ft9_syu.css';
import '../../css/z/zx4z7abfl.css';
import '../../css/h/hr_fv7unq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t_ft9_syu"/><path class="zx4z7abfl"/><path class="hr_fv7unq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-stream-broken" /></template>
