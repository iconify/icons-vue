<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gde_rkbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gde_rkbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:watch" /></template>
