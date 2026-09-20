<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rilp_eb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rilp_eb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-2-fill" /></template>
