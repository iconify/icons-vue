<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slcpo8u5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slcpo8u5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:stability-stablediffusion" /></template>
