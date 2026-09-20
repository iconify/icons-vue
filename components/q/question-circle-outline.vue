<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i4k5dgufd.css';
import '../../css/x/xb83v6b4n.css';
import '../../css/y/ym17mvbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i4k5dgufd"/><path class="xb83v6b4n"/><path clip-rule="evenodd" class="ym17mvbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-circle-outline" /></template>
