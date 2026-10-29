<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx0ze2q_o.css';
import '../../css/w/wsv04yb4u.css';
import '../../css/q/qy50xacio.css';
import '../../css/c/cv7359bwk.css';
import '../../css/z/zck36dw4l.css';
import '../../css/d/db7zur54e.css';
import '../../css/i/iis3facsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow xx0ze2q_o"/><path class="wsv04yb4u"/><path class="qy50xacio"/><path class="cv7359bwk"/><path class="zck36dw4l"/><path class="db7zur54e wm-shine"/><path class="iis3facsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:plus" /></template>
