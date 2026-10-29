<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/sla7xkb_i.css';
import '../../css/d/d8t5hybly.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/l/l8mo16qch.css';
import '../../css/c/cgczxwbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="sla7xkb_i wm-deco"/><path class="d8t5hybly wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="l8mo16qch wm-k"/><path class="cgczxwbbg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plug-blueprint" /></template>
