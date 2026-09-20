<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uij4f5b-x.css';
import '../../css/g/gx4suybiw.css';
import '../../css/i/i2ivzmcfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":141,"height":32};
const content = `<g class="uij4f5b-x"><path clip-rule="evenodd" class="gx4suybiw"/><path class="i2ivzmcfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:runpod" /></template>
