<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hx4bnxbxl.css';
import '../../css/r/r0vh99iju.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/q/qm17i3bik.css';
import '../../css/g/gsm21sbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hx4bnxbxl wm-deco"/><path class="r0vh99iju wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="qm17i3bik wm-k"/><path class="gsm21sbrt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:taxi-blueprint" /></template>
