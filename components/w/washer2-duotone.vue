<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sy6d7r2rm.css';
import '../../css/n/nltr694jb.css';
import '../../css/m/mdoeygd0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sy6d7r2rm"/><path class="nltr694jb"/><path clip-rule="evenodd" class="mdoeygd0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:washer2-duotone" /></template>
