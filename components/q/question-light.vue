<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xt1fr6buf.css';
import '../../css/f/fqf74lb2o.css';
import '../../css/j/j36fnwxrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="xt1fr6buf"/><circle class="fqf74lb2o"/><path class="j36fnwxrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:question-light" /></template>
