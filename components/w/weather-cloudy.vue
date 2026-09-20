<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee16c9d6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee16c9d6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:weather-cloudy" /></template>
