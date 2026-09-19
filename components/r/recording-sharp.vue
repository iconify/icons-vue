<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djn_kwbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djn_kwbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:recording-sharp" /></template>
