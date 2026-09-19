<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s_vgbnh1a.css';
import '../../css/a/a_5r_9oli.css';
import '../../css/v/v3k1ki33g.css';
import '../../css/x/xbm1b9a_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="s_vgbnh1a"/><path clip-rule="evenodd" class="a_5r_9oli"/><path class="v3k1ki33g"/><path class="xbm1b9a_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:pills" /></template>
