<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ecpnxtbzc.css';
import '../../css/h/hwxoqsybz.css';
import '../../css/q/qf1cubdaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ecpnxtbzc"/><path class="hwxoqsybz"/><path class="qf1cubdaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paint-roller-duotone" /></template>
