<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z08vmqjdw.css';
import '../../css/j/j0681-bpi.css';
import '../../css/e/eue9lwbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="z08vmqjdw"/><path clip-rule="evenodd" class="j0681-bpi"/><path class="eue9lwbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:travel" /></template>
