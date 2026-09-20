<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjnqghfek.css';
import '../../css/a/azukwebbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tjnqghfek"/><path class="azukwebbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nintendo" /></template>
