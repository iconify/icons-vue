<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z4uu37bfu.css';
import '../../css/d/ds9qz1atr.css';
import '../../css/d/dmo352x4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="z4uu37bfu"/><path clip-rule="evenodd" class="ds9qz1atr"/><path clip-rule="evenodd" class="dmo352x4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:opthalmology-outline" /></template>
