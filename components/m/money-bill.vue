<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ori_vdbnw.css';
import '../../css/k/k4r97xbar.css';
import '../../css/r/rt-z_tz5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ori_vdbnw"/><path class="k4r97xbar"/><path clip-rule="evenodd" class="rt-z_tz5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-bill" /></template>
