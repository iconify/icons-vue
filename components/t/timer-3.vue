<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awwgdy2er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awwgdy2er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-3" /></template>
