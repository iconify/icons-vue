<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p7m85zbxu.css';
import '../../css/c/cgs-uwvct.css';
import '../../css/g/g51thdeli.css';
import '../../css/d/d64w7pbmt.css';
import '../../css/h/h3fvscc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="p7m85zbxu"/><path class="cgs-uwvct"/><path class="g51thdeli"/><circle transform="rotate(35.072 38.356 7.483)" class="d64w7pbmt"/><circle transform="rotate(35.072 40.81 9.206)" class="h3fvscc3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:turkey" /></template>
