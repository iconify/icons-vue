<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dayz5c4na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dayz5c4na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:memory" /></template>
