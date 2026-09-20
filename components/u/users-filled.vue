<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l4k2nwwaz.css';
import '../../css/o/ouzepdbve.css';
import '../../css/h/hbxrwe5kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="l4k2nwwaz"/><ellipse class="ouzepdbve"/><path class="hbxrwe5kr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users-filled" /></template>
