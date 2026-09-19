<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bo1_r_bkn.css';
import '../../css/k/k_95onbhk.css';
import '../../css/x/xy7bfo4gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="bo1_r_bkn"/><path class="k_95onbhk"/><rect class="xy7bfo4gq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:newspaper" /></template>
