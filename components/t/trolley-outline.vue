<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jto-0ybws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jto-0ybws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trolley-outline" /></template>
