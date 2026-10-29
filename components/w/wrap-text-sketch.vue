<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a1bidkywl.css';
import '../../css/v/vx-034bzq.css';
import '../../css/l/lpju1obmb.css';
import '../../css/x/xfyogqb8v.css';
import '../../css/p/ptl8sbnfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a1bidkywl wm-k"/><path class="vx-034bzq wm-k"/><path class="lpju1obmb wm-a"/><path class="wm-a xfyogqb8v"/><path class="ptl8sbnfp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wrap-text-sketch" /></template>
