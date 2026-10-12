<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cj2g5-b5u.css';
import '../../css/k/kgcffbbmj.css';
import '../../css/m/mq2u-nbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cj2g5-b5u"/><path class="kgcffbbmj"/><path class="mq2u-nbgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rectangle-ellipsis-duotone" /></template>
