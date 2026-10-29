<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/whz-6eqqw.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/r/ri2e-qbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="whz-6eqqw"/><path class="qr4ochb5c wm-s"/><path class="ri2e-qbwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-off-duo" /></template>
