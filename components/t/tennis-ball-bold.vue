<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/htao7sagh.css';
import '../../css/u/uka4prbuv.css';
import '../../css/n/nvlvqpbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="htao7sagh"/><path class="uka4prbuv"/><path class="nvlvqpbyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tennis-ball-bold" /></template>
