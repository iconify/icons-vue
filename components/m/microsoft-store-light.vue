<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft090pbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ft090pbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-store-light" /></template>
