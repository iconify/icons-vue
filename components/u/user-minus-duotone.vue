<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d4z8ksbxz.css';
import '../../css/g/gl06rbblb.css';
import '../../css/u/u-8jrx5yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d4z8ksbxz"/><path class="gl06rbblb"/><path clip-rule="evenodd" class="u-8jrx5yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-minus-duotone" /></template>
