<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg-aetbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rg-aetbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-20" /></template>
