<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jt7qk4eua.css';
import '../../css/g/g_v_p-b4a.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/y/y6b34bbnk.css';
import '../../css/f/fqpodu9zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jt7qk4eua wm-deco"/><path class="g_v_p-b4a wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="wm-k y6b34bbnk"/><path class="fqpodu9zv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paint-roller-blueprint" /></template>
