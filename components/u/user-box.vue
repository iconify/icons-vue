<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mxc6vr24n.css';
import '../../css/t/t97kcpfjv.css';
import '../../css/j/jgjjp7t-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="mxc6vr24n"/><path class="t97kcpfjv"/><rect class="jgjjp7t-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:user-box" /></template>
