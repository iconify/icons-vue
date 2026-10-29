<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/shx7b5b7m.css';
import '../../css/e/etekexbjn.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/r/r9k-mr8cz.css';
import '../../css/d/dorpla9vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="shx7b5b7m wm-deco"/><path class="etekexbjn wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="r9k-mr8cz wm-k"/><path class="dorpla9vi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:route-blueprint" /></template>
