<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qbbx1sbmp.css';
import '../../css/s/s2ug4_b9s.css';
import '../../css/b/bnkyxhv3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="qbbx1sbmp"/><path class="s2ug4_b9s"/><path class="bnkyxhv3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tennis-ball" /></template>
