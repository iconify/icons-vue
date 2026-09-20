<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/olqgzbbek.css';
import '../../css/r/rgf_9qbzz.css';
import '../../css/m/mb6i1bdgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="olqgzbbek"/><path class="rgf_9qbzz"/><path class="mb6i1bdgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:people-nearby-bold-duotone" /></template>
