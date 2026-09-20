<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sghtszopb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sghtszopb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-add-fill" /></template>
