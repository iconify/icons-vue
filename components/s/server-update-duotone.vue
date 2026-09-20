<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bx8ysgbrh.css';
import '../../css/p/p544mhjmk.css';
import '../../css/w/wnsgfjjrv.css';
import '../../css/z/zzialb8dc.css';
import '../../css/d/dhcbq8rpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bx8ysgbrh"/><path class="p544mhjmk"/><path clip-rule="evenodd" class="wnsgfjjrv"/><path class="zzialb8dc"/><path clip-rule="evenodd" class="dhcbq8rpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-update-duotone" /></template>
