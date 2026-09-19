<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hf8y7jbvt.css';
import '../../css/f/fh-d-swvt.css';
import '../../css/r/r8sdp5bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hf8y7jbvt"/><path clip-rule="evenodd" class="fh-d-swvt"/><path class="r8sdp5bdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:syphilis-alt" /></template>
