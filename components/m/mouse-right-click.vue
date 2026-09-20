<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih6_8hbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih6_8hbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-right-click" /></template>
