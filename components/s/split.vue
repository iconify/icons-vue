<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj9x87k_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj9x87k_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:split" /></template>
