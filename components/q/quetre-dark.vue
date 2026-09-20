<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6yz8kxoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g6yz8kxoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quetre-dark" /></template>
