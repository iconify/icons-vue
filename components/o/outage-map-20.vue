<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms_f6iiek.css';
import '../../css/p/pjqmup4lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ms_f6iiek"/><path class="pjqmup4lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:outage-map-20" /></template>
