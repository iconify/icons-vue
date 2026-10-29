<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jrpbbdoby.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/h/hjheo7blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jrpbbdoby wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="hjheo7blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:table-blueprint" /></template>
