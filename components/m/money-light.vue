<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/n/nz26t1bjz.css';
import '../../css/g/gz9k5dbkr.css';
import '../../css/h/h_tsn8bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="nz26t1bjz"/><path class="gz9k5dbkr"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:money-light" /></template>
