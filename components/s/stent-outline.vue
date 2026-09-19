<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tx4ucrbrc.css';
import '../../css/p/plg4ghbsm.css';
import '../../css/a/ai58kdhbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="tx4ucrbrc"/><path clip-rule="evenodd" class="plg4ghbsm"/><path clip-rule="evenodd" class="ai58kdhbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stent-outline" /></template>
