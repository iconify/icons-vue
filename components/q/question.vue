<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/a6z4ynb6v.css';
import '../../css/f/fqf74lb2o.css';
import '../../css/v/v39n78vsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="a6z4ynb6v"/><circle class="fqf74lb2o"/><path class="v39n78vsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:question" /></template>
