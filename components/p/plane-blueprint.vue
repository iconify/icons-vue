<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fa02m5btw.css';
import '../../css/s/s60nzevdd.css';
import '../../css/a/aurd6xbhd.css';
import '../../css/t/tygsh6hqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fa02m5btw wm-deco"/><path class="s60nzevdd wm-deco"/><path class="aurd6xbhd wm-deco"/><path class="tygsh6hqg wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plane-blueprint" /></template>
