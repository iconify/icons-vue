<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke_bx8-uq.css';
import '../../css/m/mqx34y6qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="ke_bx8-uq"/><rect class="mqx34y6qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rows-filled" /></template>
