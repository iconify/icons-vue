<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/uk_v7bife.css';
import '../../css/b/b1w3ycbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="uk_v7bife"/><path class="b1w3ycbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:slack" /></template>
