<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bottp98ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bottp98ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-horizontal-outline" /></template>
