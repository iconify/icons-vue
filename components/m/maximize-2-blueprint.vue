<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/pjfvu7rlw.css';
import '../../css/b/bxjv56brc.css';
import '../../css/j/jdk8orm8z.css';
import '../../css/y/y822yac6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="pjfvu7rlw wm-deco"/><path class="bxjv56brc wm-deco"/><path class="jdk8orm8z"/><path class="y822yac6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-2-blueprint" /></template>
