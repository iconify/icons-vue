<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pltvjvbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pltvjvbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-partlycloudy" /></template>
