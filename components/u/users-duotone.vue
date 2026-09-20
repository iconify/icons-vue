<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r6la0c6vv.css';
import '../../css/s/sftxd8wtz.css';
import '../../css/l/l4k2nwwaz.css';
import '../../css/o/ouzepdbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="r6la0c6vv"/><ellipse class="sftxd8wtz"/><circle class="l4k2nwwaz"/><ellipse class="ouzepdbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users-duotone" /></template>
