<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b-l6dcceu.css';
import '../../css/r/r5jmk_bor.css';
import '../../css/i/i21ar1oaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b-l6dcceu"/><path class="r5jmk_bor"/><path class="i21ar1oaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:three-square-filled" /></template>
