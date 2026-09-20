<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucq63j0-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucq63j0-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-arrow-right" /></template>
