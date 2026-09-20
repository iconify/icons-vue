<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pnw53uboj.css';
import '../../css/h/h5vc5jbye.css';
import '../../css/w/wqwixuz1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pnw53uboj"/><path class="h5vc5jbye"/><path class="wqwixuz1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:monitor-phone-duotone" /></template>
