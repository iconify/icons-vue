<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruogetb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruogetb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thermostat-auto" /></template>
