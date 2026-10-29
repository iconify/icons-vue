<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/x/xlsrwfbva.css';
import '../../css/l/ldpgispni.css';
import '../../css/v/v5jdyxbhx.css';
import '../../css/e/epgciubws.css';
import '../../css/x/xaf6cob8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco xlsrwfbva"/><path class="ldpgispni wm-deco"/><path class="v5jdyxbhx wm-deco"/><path class="epgciubws wm-k"/><path class="wm-a xaf6cob8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:projector-blueprint" /></template>
