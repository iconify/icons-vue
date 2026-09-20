<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imxzj81sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imxzj81sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thermostat-box-auto" /></template>
