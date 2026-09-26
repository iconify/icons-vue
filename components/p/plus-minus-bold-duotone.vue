<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hl9_mob0i.css';
import '../../css/n/nub6v-blk.css';
import '../../css/l/lrqda5b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hl9_mob0i"/><path clip-rule="evenodd" class="nub6v-blk"/><path class="lrqda5b7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plus-minus-bold-duotone" /></template>
