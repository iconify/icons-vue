<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj_2k2vxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj_2k2vxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:office-building-check" /></template>
