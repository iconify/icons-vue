<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/luy9z6pgm.css';
import '../../css/e/ehvke5qnp.css';
import '../../css/a/am157rupi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="luy9z6pgm"/><path class="ehvke5qnp"/><path clip-rule="evenodd" class="am157rupi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:nightstand4-filled" /></template>
