<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej1jc3dov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej1jc3dov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:thermostat-alert" /></template>
