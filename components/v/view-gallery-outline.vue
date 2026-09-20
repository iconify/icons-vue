<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mad0qzn3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mad0qzn3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-gallery-outline" /></template>
