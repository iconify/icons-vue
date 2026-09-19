<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i5ewysb1u.css';
import '../../css/t/t7pas2b0i.css';
import '../../css/y/yeio0pa9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i5ewysb1u"/><path class="t7pas2b0i"/><path clip-rule="evenodd" class="yeio0pa9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:tap-double" /></template>
