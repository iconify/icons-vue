<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/u8jvivt2y.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/o/o3tkwvr2o.css';
import '../../css/x/xnp0x9brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="u8jvivt2y wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="o3tkwvr2o wm-k"/><path class="wm-k xnp0x9brw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-circle-blueprint" /></template>
