<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piopy9w_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piopy9w_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:option-solid" /></template>
