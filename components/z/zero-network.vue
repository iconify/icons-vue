<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa41-ac5j.css';
import '../../css/m/mn-fhob2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa41-ac5j"/><path clip-rule="evenodd" class="mn-fhob2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zero-network" /></template>
