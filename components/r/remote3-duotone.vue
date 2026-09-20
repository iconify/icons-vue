<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c6y0h7bnk.css';
import '../../css/c/c_1gxwnlz.css';
import '../../css/g/gvutyp9ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c6y0h7bnk"/><path class="c_1gxwnlz"/><path clip-rule="evenodd" class="gvutyp9ik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:remote3-duotone" /></template>
