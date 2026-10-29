<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wo259ue5g.css';
import '../../css/z/zb6mz35nb.css';
import '../../css/g/gv5fj_e6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wo259ue5g"/><path class="wm-a zb6mz35nb"/><path class="gv5fj_e6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:vr-headset-duo" /></template>
