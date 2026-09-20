<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v3wsr-blu.css';
import '../../css/g/ge5ik32ip.css';
import '../../css/p/p0-no_b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="v3wsr-blu"/><path class="ge5ik32ip"/><path class="p0-no_b3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-select-duotone" /></template>
