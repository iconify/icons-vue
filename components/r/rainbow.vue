<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tn07yfl-o.css';
import '../../css/f/fmgs8jbtv.css';
import '../../css/n/npaxttsgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tn07yfl-o"/><path class="fmgs8jbtv"/><path class="npaxttsgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rainbow" /></template>
