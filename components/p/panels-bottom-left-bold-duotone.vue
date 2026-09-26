<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fu2ooubtt.css';
import '../../css/m/m0sh7ccsz.css';
import '../../css/u/uvqytmbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fu2ooubtt"/><path class="m0sh7ccsz"/><path class="uvqytmbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-left-bold-duotone" /></template>
