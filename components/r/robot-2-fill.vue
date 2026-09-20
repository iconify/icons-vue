<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omn_tbces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omn_tbces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:robot-2-fill" /></template>
