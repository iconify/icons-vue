<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jrfwjg2rr.css';
import '../../css/g/g9weubcys.css';
import '../../css/l/lpx720bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jrfwjg2rr"/><path class="g9weubcys"/><path class="lpx720bup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stopwatch-play-duotone" /></template>
