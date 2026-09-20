<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdu4dczmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdu4dczmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:power-norway-light" /></template>
