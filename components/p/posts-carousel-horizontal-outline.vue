<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w30p9ms3q.css';
import '../../css/b/bxeul--al.css';
import '../../css/g/gskkfws9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w30p9ms3q"/><path class="bxeul--al"/><path class="gskkfws9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-horizontal-outline" /></template>
