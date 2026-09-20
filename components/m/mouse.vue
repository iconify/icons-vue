<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxf00_bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf00_bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:mouse" /></template>
