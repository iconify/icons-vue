<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rov56qb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rov56qb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:newspaper-remove" /></template>
