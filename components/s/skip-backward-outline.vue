<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq97zwull.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq97zwull"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-backward-outline" /></template>
