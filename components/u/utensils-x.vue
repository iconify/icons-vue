<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnp4mc_bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnp4mc_bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:utensils-x" /></template>
