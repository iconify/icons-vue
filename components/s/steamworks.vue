<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx2_dxqau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx2_dxqau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:steamworks" /></template>
