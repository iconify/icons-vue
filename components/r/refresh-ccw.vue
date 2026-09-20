<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/ngnrt3bip.css';
import '../../css/i/im44ngbpl.css';
import '../../css/q/qb_upbbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ngnrt3bip"/><path class="im44ngbpl"/><path class="qb_upbbvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:refresh-ccw" /></template>
