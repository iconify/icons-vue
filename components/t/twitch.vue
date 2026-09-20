<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lbuecfbqn.css';
import '../../css/y/ylik4k7po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="lbuecfbqn"/><path class="ylik4k7po"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:twitch" /></template>
