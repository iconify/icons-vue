<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdala_bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdala_bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:u-turn" /></template>
