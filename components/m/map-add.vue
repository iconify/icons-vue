<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdbf7hbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdbf7hbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-add" /></template>
