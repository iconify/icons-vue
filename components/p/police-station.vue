<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjss92b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjss92b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:police-station" /></template>
