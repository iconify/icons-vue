<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyto0dbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyto0dbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zara" /></template>
