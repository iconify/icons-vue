<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cfkicbk9n.css';
import '../../css/w/wnxmdjbom.css';
import '../../css/p/pokq2rrtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cfkicbk9n"/><path class="wnxmdjbom"/><path class="pokq2rrtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-split-duo" /></template>
