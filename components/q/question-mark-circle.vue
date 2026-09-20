<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/omgxo1t4m.css';
import '../../css/r/rbmb9m21o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="omgxo1t4m"/><path clip-rule="evenodd" class="rbmb9m21o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:question-mark-circle" /></template>
