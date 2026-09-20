<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/stzn1tb6p.css';
import '../../css/u/u0jy2c12v.css';
import '../../css/n/n8guz-bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="stzn1tb6p"/><circle class="u0jy2c12v"/><path class="n8guz-bso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:msg-bubble-user-filled" /></template>
