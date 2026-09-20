<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y_cyddb_p.css';
import '../../css/i/ihhtxk45i.css';
import '../../css/d/dehs78hfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y_cyddb_p"/><path class="ihhtxk45i"/><path clip-rule="evenodd" class="dehs78hfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-up" /></template>
