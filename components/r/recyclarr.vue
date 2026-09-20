<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsr5ihb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsr5ihb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:recyclarr" /></template>
