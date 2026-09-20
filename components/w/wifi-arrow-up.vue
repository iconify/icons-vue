<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jav0ifzme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jav0ifzme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-arrow-up" /></template>
