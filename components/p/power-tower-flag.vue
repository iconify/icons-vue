<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qivw3q8uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qivw3q8uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-flag" /></template>
