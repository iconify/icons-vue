<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/sjhkt6bhu.css';
import '../../css/j/jrapsbbrm.css';
import '../../css/b/bqm3gtbge.css';
import '../../css/k/kymm-cb-b.css';
import '../../css/j/jgogmk-tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="sjhkt6bhu wm-shadow"/><path class="jrapsbbrm wm-shadow"/><path class="bqm3gtbge"/><path class="kymm-cb-b"/><path class="jgogmk-tb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:pipette" /></template>
