<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5m86r8df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5m86r8df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shop-location-outline" /></template>
