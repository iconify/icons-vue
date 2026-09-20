<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cxok09bpt.css';
import '../../css/l/lus2b4bfg.css';
import '../../css/o/owl243b6x.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cxok09bpt"/><path clip-rule="evenodd" class="lus2b4bfg"/><path clip-rule="evenodd" class="owl243b6x"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:next-track-circle-off" /></template>
