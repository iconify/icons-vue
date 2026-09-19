<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/w/w4xt16bhc.css';
import '../../css/l/l3tkt12ja.css';
import '../../css/r/r_99_sgdv.css';
import '../../css/c/ck8h4nb_y.css';
import '../../css/t/tkuvc-5zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="w4xt16bhc"/><path class="l3tkt12ja"/><path class="r_99_sgdv"/><circle class="ck8h4nb_y"/><path class="tkuvc-5zm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:music-2-thin" /></template>
