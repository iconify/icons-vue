<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cxh34dbkk.css';
import '../../css/g/gx7_0oe9s.css';
import '../../css/t/tfa_rob_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cxh34dbkk"/><path class="gx7_0oe9s"/><path class="tfa_rob_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:television" /></template>
