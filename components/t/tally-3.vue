<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igi1yv4ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igi1yv4ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tally-3" /></template>
