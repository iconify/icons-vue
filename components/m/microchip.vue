<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kynv3_bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kynv3_bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:microchip" /></template>
