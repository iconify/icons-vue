<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gck084bsd.css';
import '../../css/l/ly96r7zqe.css';
import '../../css/c/cfa4tobzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gck084bsd"/><path class="ly96r7zqe"/><path class="cfa4tobzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-vertical-outline" /></template>
