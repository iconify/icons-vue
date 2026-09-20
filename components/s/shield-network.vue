<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_sn057m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_sn057m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-network" /></template>
