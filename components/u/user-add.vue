<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c5ik97bsm.css';
import '../../css/c/c4pd3lb9b.css';
import '../../css/f/f9fxuac1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="c5ik97bsm"/><path class="c4pd3lb9b"/><path clip-rule="evenodd" class="f9fxuac1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-add" /></template>
