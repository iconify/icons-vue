<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wz0rp_ekf.css';
import '../../css/p/pf1_oxqio.css';
import '../../css/l/lfesz3put.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="wz0rp_ekf"/><path class="pf1_oxqio"/><path class="lfesz3put"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-yield" /></template>
