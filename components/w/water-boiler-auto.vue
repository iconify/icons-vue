<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snaj7oq1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snaj7oq1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:water-boiler-auto" /></template>
