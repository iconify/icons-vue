<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/grc9tmbtv.css';
import '../../css/q/qi-z61bjd.css';
import '../../css/g/goueu-bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="grc9tmbtv"/><path clip-rule="evenodd" class="qi-z61bjd"/><path clip-rule="evenodd" class="goueu-bkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:user-circle-bold" /></template>
