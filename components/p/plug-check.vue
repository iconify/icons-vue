<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj7443xlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj7443xlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plug-check" /></template>
