<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cc1czgsqt.css';
import '../../css/c/c_zdt_bqs.css';
import '../../css/l/lw_g68b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cc1czgsqt"/><path class="c_zdt_bqs"/><path class="lw_g68b2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-block-rounded-bold-duotone" /></template>
