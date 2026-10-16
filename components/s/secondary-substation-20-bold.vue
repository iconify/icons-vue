<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnex-cbcf.css';
import '../../css/m/m480pab_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pnex-cbcf"/><path class="m480pab_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:secondary-substation-20-bold" /></template>
