<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkxtgbcbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkxtgbcbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-arrow-down-outline" /></template>
