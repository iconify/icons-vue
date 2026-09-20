<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c5ik97bsm.css';
import '../../css/i/ihebqlels.css';
import '../../css/z/z9bpx178d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="c5ik97bsm"/><path class="ihebqlels"/><path clip-rule="evenodd" class="z9bpx178d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-add2" /></template>
