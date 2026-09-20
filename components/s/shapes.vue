<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lklawe5cz.css';
import '../../css/j/j40labcrn.css';
import '../../css/g/gv3k2ybsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lklawe5cz"/><rect class="j40labcrn"/><path class="gv3k2ybsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shapes" /></template>
