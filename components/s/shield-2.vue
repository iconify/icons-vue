<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr_5rabpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr_5rabpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shield-2" /></template>
