<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/w/wa_36nb_w.css';
import '../../css/d/djv7kdbjb.css';
import '../../css/p/pbtr10c0j.css';
import '../../css/z/ztlt9mb-t.css';
import '../../css/d/dah5g1k0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wa_36nb_w wm-deco"/><path class="djv7kdbjb wm-deco"/><path class="pbtr10c0j wm-deco"/><path class="ztlt9mb-t"/><path class="dah5g1k0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:navigation-blueprint" /></template>
