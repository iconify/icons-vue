<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhc2ufb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhc2ufb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:owl" /></template>
