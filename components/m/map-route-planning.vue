<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iuisc46tr.css';
import '../../css/s/stl-wtb-o.css';
import '../../css/a/av3m8fbrw.css';
import '../../css/g/ggljhkv3p.css';
import '../../css/s/srij2hbwk.css';
import '../../css/p/p4x5sk9nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iuisc46tr"/><path class="stl-wtb-o"/><g class="av3m8fbrw"><path class="ggljhkv3p"/><path class="srij2hbwk"/></g><path class="p4x5sk9nw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-route-planning" /></template>
