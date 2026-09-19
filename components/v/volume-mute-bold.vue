<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p67h9fzui.css';
import '../../css/x/x3ma9xbzh.css';
import '../../css/d/dkmidwbcl.css';
import '../../css/o/oa8805bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="p67h9fzui"/><path class="x3ma9xbzh"/><path class="dkmidwbcl"/><path class="oa8805bxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:volume-mute-bold" /></template>
