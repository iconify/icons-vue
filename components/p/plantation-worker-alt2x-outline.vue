<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lem80_bri.css';
import '../../css/e/e__bb0b3o.css';
import '../../css/g/g4__c4brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lem80_bri"/><path class="e__bb0b3o"/><path clip-rule="evenodd" class="g4__c4brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:plantation-worker-alt2x-outline" /></template>
