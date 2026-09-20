<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m09ees1ha.css';
import '../../css/b/b3j-b8zmr.css';
import '../../css/p/pn3q5-w6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m09ees1ha"/><path class="b3j-b8zmr"/><path clip-rule="evenodd" class="pn3q5-w6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:planet2-duotone" /></template>
