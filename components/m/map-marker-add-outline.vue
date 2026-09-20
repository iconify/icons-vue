<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lol-b6qtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lol-b6qtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-marker-add-outline" /></template>
