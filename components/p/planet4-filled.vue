<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n6hujrb1l.css';
import '../../css/u/ujb0nvh4p.css';
import '../../css/t/t2h-yb7be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n6hujrb1l"/><path class="ujb0nvh4p"/><path clip-rule="evenodd" class="t2h-yb7be"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:planet4-filled" /></template>
