<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uup_hebcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uup_hebcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-image-outline" /></template>
