<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyygioguv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1664};
const content = `<path class="dyygioguv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:microchip" /></template>
