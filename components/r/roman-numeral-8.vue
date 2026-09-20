<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmjhv4bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmjhv4bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roman-numeral-8" /></template>
