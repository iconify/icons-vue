<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n5u5o1ykq.css';
import '../../css/l/lonii6b0k.css';
import '../../css/a/a7hds4b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="n5u5o1ykq"/><path clip-rule="evenodd" class="lonii6b0k"/><path clip-rule="evenodd" class="a7hds4b4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:travel-alt" /></template>
