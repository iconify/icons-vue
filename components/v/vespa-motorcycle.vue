<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c-44blbvn.css';
import '../../css/e/evuc5vbmd.css';
import '../../css/n/n_ea_d4_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="c-44blbvn"/><path clip-rule="evenodd" class="evuc5vbmd"/><path class="n_ea_d4_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vespa-motorcycle" /></template>
