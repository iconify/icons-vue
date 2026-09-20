<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk9hffbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk9hffbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-windy" /></template>
