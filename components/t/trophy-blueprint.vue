<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/s4cfjypce.css';
import '../../css/s/sbsfawmcu.css';
import '../../css/d/dlmywhbph.css';
import '../../css/i/ieoysimau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="s4cfjypce wm-deco"/><path class="sbsfawmcu wm-deco"/><path class="dlmywhbph wm-deco"/><path class="ieoysimau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trophy-blueprint" /></template>
