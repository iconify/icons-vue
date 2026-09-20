<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yg620pbav.css';
import '../../css/b/brhnrtb_n.css';
import '../../css/n/n06a_8beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yg620pbav"/><path class="brhnrtb_n"/><path clip-rule="evenodd" class="n06a_8beg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sliders" /></template>
