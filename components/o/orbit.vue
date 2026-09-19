<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqd8fcboz.css';
import '../../css/k/kl149rbvc.css';
import '../../css/c/cnrn66j_x.css';
import '../../css/g/gkp1rfbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><circle class="kl149rbvc"/><path class="cnrn66j_x"/><path class="gkp1rfbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gala:orbit" /></template>
