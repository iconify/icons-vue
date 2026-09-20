<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pswcvcb4c.css';
import '../../css/n/n5mi1zbsm.css';
import '../../css/u/uw00s73td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pswcvcb4c"/><path class="n5mi1zbsm"/><path clip-rule="evenodd" class="uw00s73td"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-10-seconds-back-bold" /></template>
