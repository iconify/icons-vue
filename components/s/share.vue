<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2x_72vy.css';
import '../../css/o/ottjqxlpz.css';
import '../../css/h/hu7q9bbvj.css';
import '../../css/i/iui5ovbws.css';
import '../../css/w/wr-sfrbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><circle class="ottjqxlpz"/><circle class="hu7q9bbvj"/><circle class="iui5ovbws"/><path class="wr-sfrbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:share" /></template>
