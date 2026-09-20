<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f_wlggf6j.css';
import '../../css/l/la4svweqi.css';
import '../../css/p/p74w0sexm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="f_wlggf6j"/><circle class="la4svweqi"/><path clip-rule="evenodd" class="p74w0sexm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:routing3-duotone" /></template>
