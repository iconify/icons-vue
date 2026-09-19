<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/owfeisrst.css';
import '../../css/p/putt_dyyu.css';
import '../../css/l/lr9b8khur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="owfeisrst"/><path clip-rule="evenodd" class="putt_dyyu"/><path class="lr9b8khur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:pill-print" /></template>
