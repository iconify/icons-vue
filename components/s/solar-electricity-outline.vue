<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwlc9-kij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwlc9-kij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:solar-electricity-outline" /></template>
