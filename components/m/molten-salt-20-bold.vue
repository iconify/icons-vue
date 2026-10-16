<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp_3l1bkn.css';
import '../../css/m/myhv_wb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fp_3l1bkn"/><path class="myhv_wb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:molten-salt-20-bold" /></template>
