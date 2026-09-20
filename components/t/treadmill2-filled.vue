<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mkih2u7bz.css';
import '../../css/s/spvqwdb2l.css';
import '../../css/t/td2s06bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mkih2u7bz"/><path clip-rule="evenodd" class="spvqwdb2l"/><path class="td2s06bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:treadmill2-filled" /></template>
