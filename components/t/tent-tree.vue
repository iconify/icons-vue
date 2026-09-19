<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p9vjoqtlo.css';
import '../../css/w/wubqooj-f.css';
import '../../css/o/onxfb1bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="p9vjoqtlo"/><path class="wubqooj-f"/><path class="onxfb1bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tent-tree" /></template>
