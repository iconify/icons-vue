<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfamm1_av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfamm1_av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-alert-outline" /></template>
