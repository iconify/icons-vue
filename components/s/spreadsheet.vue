<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_p8vvblx.css';
import '../../css/x/xeykeqb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_p8vvblx"/><path class="xeykeqb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:spreadsheet" /></template>
