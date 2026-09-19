<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iw2x1acko.css';
import '../../css/r/rax87kb-g.css';
import '../../css/m/mtlu6ijui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="iw2x1acko"/><path class="rax87kb-g"/><path class="mtlu6ijui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-lifting-weights" /></template>
