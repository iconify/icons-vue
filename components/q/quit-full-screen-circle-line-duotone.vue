<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qu7_qcjgl.css';
import '../../css/i/ip3qm20ze.css';
import '../../css/k/kr99ulpjv.css';
import '../../css/u/u66s-fbqm.css';
import '../../css/d/doy9q4b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qu7_qcjgl"/><path class="ip3qm20ze"/><path class="kr99ulpjv"/><path class="u66s-fbqm"/><circle class="doy9q4b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-circle-line-duotone" /></template>
