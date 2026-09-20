<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6zdiyx0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6zdiyx0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:uptime-kuma" /></template>
