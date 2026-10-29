<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l0ybcbb1u.css';
import '../../css/c/cmnsdn4hz.css';
import '../../css/r/rxk3pwbcz.css';
import '../../css/j/jq-f4actp.css';
import '../../css/d/djj_a9nwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l0ybcbb1u wm-k"/><path class="cmnsdn4hz wm-k"/><path class="rxk3pwbcz wm-k"/><path class="jq-f4actp wm-shine"/><path class="djj_a9nwa wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:star" /></template>
