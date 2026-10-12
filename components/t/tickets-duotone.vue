<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xq6mjller.css';
import '../../css/o/olznywbdz.css';
import '../../css/b/bpvbic07d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xq6mjller"/><path class="olznywbdz"/><path class="bpvbic07d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tickets-duotone" /></template>
