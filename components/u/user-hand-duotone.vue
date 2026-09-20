<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wo0pu3bhk.css';
import '../../css/i/io57_vhgi.css';
import '../../css/d/dtl23o_xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wo0pu3bhk"/><path class="io57_vhgi"/><circle class="dtl23o_xq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-hand-duotone" /></template>
