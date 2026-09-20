<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj85o5bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj85o5bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weight-gram" /></template>
