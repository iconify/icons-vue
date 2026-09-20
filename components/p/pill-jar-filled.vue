<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z1y3f6bsl.css';
import '../../css/o/oqas85b_h.css';
import '../../css/x/xi4oud6jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z1y3f6bsl"/><path clip-rule="evenodd" class="oqas85b_h"/><path class="xi4oud6jq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pill-jar-filled" /></template>
