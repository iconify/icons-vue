<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq4c_3bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vq4c_3bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:transfer" /></template>
