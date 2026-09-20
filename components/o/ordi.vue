<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpwtmbbva.css';
import '../../css/w/w3w4p5b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpwtmbbva"/><path clip-rule="evenodd" class="w3w4p5b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ordi" /></template>
