<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgr7q-t0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgr7q-t0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-help" /></template>
