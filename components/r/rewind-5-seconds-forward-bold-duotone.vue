<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kfrjlxb8w.css';
import '../../css/t/tjh65cbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kfrjlxb8w"/><path clip-rule="evenodd" class="tjh65cbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-5-seconds-forward-bold-duotone" /></template>
