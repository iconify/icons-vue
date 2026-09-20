<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y4rb44b0t.css';
import '../../css/i/i5w7s1btf.css';
import '../../css/w/wl2no6bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y4rb44b0t"/><path class="i5w7s1btf"/><path class="wl2no6bnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:password3" /></template>
