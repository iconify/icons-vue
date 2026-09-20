<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gx-369bjn.css';
import '../../css/r/rrhjx2bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 4)" class="bi12bsetm"><path class="gx-369bjn"/><circle class="rrhjx2bmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:wallet" /></template>
