<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlo4be-zl.css';
import '../../css/l/lswyakbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qlo4be-zl"/><path class="lswyakbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-insulation-20-bold" /></template>
