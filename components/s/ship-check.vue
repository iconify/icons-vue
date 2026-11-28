<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmedxiosp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmedxiosp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ship-check" /></template>
