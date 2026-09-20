<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bn8y6suty.css';
import '../../css/f/fyibwt4bd.css';
import '../../css/h/hhd17-bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bn8y6suty"/><path clip-rule="evenodd" class="fyibwt4bd"/><path class="hhd17-bgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-replace-duotone" /></template>
