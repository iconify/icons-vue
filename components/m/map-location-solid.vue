<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi5-9xmbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fi5-9xmbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:map-location-solid" /></template>
