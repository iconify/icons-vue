<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnwwm778c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnwwm778c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mapbox" /></template>
