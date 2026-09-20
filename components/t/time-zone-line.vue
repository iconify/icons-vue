<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5vgau4oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5vgau4oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:time-zone-line" /></template>
