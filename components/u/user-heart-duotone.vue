<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a8neukw-z.css';
import '../../css/n/nhwshp5mj.css';
import '../../css/l/luthdg-vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="a8neukw-z"/><path clip-rule="evenodd" class="nhwshp5mj"/><path class="luthdg-vg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-heart-duotone" /></template>
