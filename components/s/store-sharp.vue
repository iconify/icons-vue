<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbw1u09ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbw1u09ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:store-sharp" /></template>
