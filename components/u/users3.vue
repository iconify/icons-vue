<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s7-ubbcgv.css';
import '../../css/g/g0uevob0y.css';
import '../../css/r/rzuh_2b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s7-ubbcgv"/><path class="g0uevob0y"/><path clip-rule="evenodd" class="rzuh_2b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users3" /></template>
