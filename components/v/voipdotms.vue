<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqn9yz3js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqn9yz3js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:voipdotms" /></template>
