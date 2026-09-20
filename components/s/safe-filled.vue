<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i5jzghb3e.css';
import '../../css/u/um-4_bc_j.css';
import '../../css/n/n1c7bqrrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i5jzghb3e"/><path clip-rule="evenodd" class="um-4_bc_j"/><path clip-rule="evenodd" class="n1c7bqrrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:safe-filled" /></template>
