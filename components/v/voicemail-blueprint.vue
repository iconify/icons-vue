<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gpuvf8bwr.css';
import '../../css/o/o-tsjlamj.css';
import '../../css/m/m9avzl1wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gpuvf8bwr wm-deco"/><path class="o-tsjlamj wm-deco"/><path class="m9avzl1wk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:voicemail-blueprint" /></template>
