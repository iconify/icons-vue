<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bcrkiyb6q.css';
import '../../css/f/fv_3rybfk.css';
import '../../css/z/zlubvxnlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bcrkiyb6q"/><path class="fv_3rybfk"/><path clip-rule="evenodd" class="zlubvxnlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:varicose-vein-outline" /></template>
