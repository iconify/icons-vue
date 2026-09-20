<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixr33tota.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ixr33tota"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:map-location-remix" /></template>
