<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/e/e6ropcc-d.css';
import '../../css/v/vak-z7b5k.css';
import '../../css/o/ogmfbuu8l.css';
import '../../css/j/jmkhylajy.css';
import '../../css/t/tfiky1b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="e6ropcc-d wm-deco"/><path class="vak-z7b5k wm-deco"/><path class="ogmfbuu8l wm-k"/><path class="jmkhylajy wm-a"/><path class="tfiky1b5f wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:text-cursor-blueprint" /></template>
