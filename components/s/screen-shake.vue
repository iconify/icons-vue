<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tbxfxzvwf.css';
import '../../css/i/i7or708cv.css';
import '../../css/f/firyp-b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="tbxfxzvwf"/><path clip-rule="evenodd" class="i7or708cv"/><path class="firyp-b6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:screen-shake" /></template>
