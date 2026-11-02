<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm_uf7cdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_uf7cdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:three-quarters-circle-dash-fill" /></template>
