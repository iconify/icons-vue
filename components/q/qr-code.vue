<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aea_ip7em.css';
import '../../css/g/gze3pwb9p.css';
import '../../css/i/iaw_wybdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="aea_ip7em"/><path class="gze3pwb9p"/><path class="iaw_wybdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:qr-code" /></template>
