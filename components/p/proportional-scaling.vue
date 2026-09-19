<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/b/b0xhw3gtc.css';
import '../../css/f/foyc2nb7z.css';
import '../../css/b/btfw9mbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="b0xhw3gtc"/><path class="foyc2nb7z"/><path class="btfw9mbtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:proportional-scaling" /></template>
