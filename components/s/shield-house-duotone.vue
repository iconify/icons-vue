<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mfvnync4s.css';
import '../../css/z/zxvnpccay.css';
import '../../css/c/chqik1qby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mfvnync4s"/><path class="zxvnpccay"/><path class="chqik1qby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-house-duotone" /></template>
