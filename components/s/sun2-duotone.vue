<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kf0_gw6sp.css';
import '../../css/g/g23mak7rg.css';
import '../../css/j/jgbdxybfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kf0_gw6sp"/><path clip-rule="evenodd" class="g23mak7rg"/><path class="jgbdxybfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sun2-duotone" /></template>
