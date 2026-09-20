<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/ha3f25bxe.css';
import '../../css/i/iksb9rpzr.css';
import '../../css/n/n13mhtbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ha3f25bxe"/><path class="iksb9rpzr"/><path clip-rule="evenodd" class="n13mhtbfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-plus-outline" /></template>
