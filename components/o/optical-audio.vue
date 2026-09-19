<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/ddk587bmb.css';
import '../../css/w/wtyo39cge.css';
import '../../css/v/vuct_acof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ddk587bmb"/><path class="wtyo39cge"/><path class="vuct_acof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:optical-audio" /></template>
