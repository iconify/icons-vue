<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j615gdcks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j615gdcks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tiktok" /></template>
