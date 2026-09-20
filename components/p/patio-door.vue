<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us55ghb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us55ghb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:patio-door" /></template>
