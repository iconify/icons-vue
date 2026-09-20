<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/cqnrdhb3z.css';
import '../../css/s/sl9uo94_w.css';
import '../../css/c/cat56tugw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cqnrdhb3z"/><path class="sl9uo94_w"/><path class="cat56tugw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-close-dashed-sharp-fill" /></template>
