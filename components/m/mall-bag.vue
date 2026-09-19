<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/z/zeb2u5bnn.css';
import '../../css/d/da5c6acvy.css';
import '../../css/r/rfi36zaxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="zeb2u5bnn"/><path class="da5c6acvy"/><path class="rfi36zaxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:mall-bag" /></template>
