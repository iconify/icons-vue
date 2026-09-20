<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwnjo2bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwnjo2bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tally-mark-2" /></template>
