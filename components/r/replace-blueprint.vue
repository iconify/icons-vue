<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/x/x8undcbyj.css';
import '../../css/f/fm1mx9bkd.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/r/rhvi5vbnt.css';
import '../../css/z/zltg-z8yh.css';
import '../../css/x/xe04_zb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco x8undcbyj"/><path class="fm1mx9bkd wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="rhvi5vbnt wm-k"/><path class="wm-a zltg-z8yh"/><path class="wm-a xe04_zb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:replace-blueprint" /></template>
