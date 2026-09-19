<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdlpb_b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="mdlpb_b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:vine" /></template>
