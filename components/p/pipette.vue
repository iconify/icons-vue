<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_oaxmmyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_oaxmmyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pipette" /></template>
