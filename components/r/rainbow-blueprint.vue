<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bt6g2bfub.css';
import '../../css/r/rd4yxbljb.css';
import '../../css/d/dsnrk86ar.css';
import '../../css/r/r85x9nj_w.css';
import '../../css/k/k0a7hrljc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bt6g2bfub wm-deco"/><path class="rd4yxbljb wm-deco"/><path class="dsnrk86ar wm-k"/><path class="r85x9nj_w wm-a"/><path class="k0a7hrljc wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rainbow-blueprint" /></template>
