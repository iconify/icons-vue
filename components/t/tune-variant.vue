<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vls5gbfof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vls5gbfof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tune-variant" /></template>
