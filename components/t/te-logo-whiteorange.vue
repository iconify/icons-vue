<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewxfdn_wl.css';
import '../../css/y/y51mhybdb.css';
import '../../css/u/udkm6e2mv.css';
import '../../css/j/j5582lbug.css';
import '../../css/m/ml-o_2bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":570,"height":104};
const content = `<path class="ewxfdn_wl"/><path class="y51mhybdb"/><path class="udkm6e2mv"/><circle class="j5582lbug"/><path class="ml-o_2bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:te-logo-whiteorange" /></template>
