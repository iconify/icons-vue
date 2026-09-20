<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k26ca1srb.css';
import '../../css/x/x58ix0ngu.css';
import '../../css/z/zuqh_gv5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k26ca1srb"/><path class="x58ix0ngu"/><path clip-rule="evenodd" class="zuqh_gv5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-square-outline" /></template>
