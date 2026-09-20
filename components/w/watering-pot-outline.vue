<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgtd15b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgtd15b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:watering-pot-outline" /></template>
