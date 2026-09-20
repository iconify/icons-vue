<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p8vmmtt7r.css';
import '../../css/s/sy99kq9ei.css';
import '../../css/u/u_4at9_6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p8vmmtt7r"/><path class="sy99kq9ei"/><path clip-rule="evenodd" class="u_4at9_6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-left-bold" /></template>
