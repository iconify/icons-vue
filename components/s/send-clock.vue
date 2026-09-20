<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hsi9apijf.css';
import '../../css/b/b0xtd884y.css';
import '../../css/j/jm47mgbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hsi9apijf"/><path class="b0xtd884y"/><path clip-rule="evenodd" class="jm47mgbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:send-clock" /></template>
