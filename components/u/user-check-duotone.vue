<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d4z8ksbxz.css';
import '../../css/o/o_0l1hoku.css';
import '../../css/g/gl06rbblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d4z8ksbxz"/><path clip-rule="evenodd" class="o_0l1hoku"/><path class="gl06rbblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-check-duotone" /></template>
