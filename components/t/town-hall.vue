<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb9k3_2ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb9k3_2ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:town-hall" /></template>
