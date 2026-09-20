<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q96fchb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q96fchb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-industrial" /></template>
