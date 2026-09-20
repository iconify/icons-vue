<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oky9phvzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oky9phvzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-rotate-portrait" /></template>
