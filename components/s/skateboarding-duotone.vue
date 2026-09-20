<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s1hme5bwb.css';
import '../../css/l/lm_nrwi7b.css';
import '../../css/b/b9a6538vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s1hme5bwb"/><path class="lm_nrwi7b"/><path class="b9a6538vj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:skateboarding-duotone" /></template>
