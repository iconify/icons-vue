<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n093jabjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n093jabjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-marker-off-outline" /></template>
