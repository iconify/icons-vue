<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gtmxuwkrn.css';
import '../../css/v/v0zur3bmx.css';
import '../../css/n/n3cj5wcax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gtmxuwkrn"/><path class="v0zur3bmx"/><path class="n3cj5wcax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mic2-duotone" /></template>
