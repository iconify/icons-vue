<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hfb4gfroc.css';
import '../../css/b/b5vz60bpb.css';
import '../../css/e/epu2q02ta.css';
import '../../css/f/fmqt1fbbf.css';
import '../../css/q/q7gyq3xar.css';
import '../../css/g/gkwrxymat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hfb4gfroc wm-deco"/><path class="b5vz60bpb wm-deco"/><path class="epu2q02ta wm-k"/><path class="fmqt1fbbf wm-a"/><path class="q7gyq3xar wm-k"/><path class="gkwrxymat wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:subscript-blueprint" /></template>
