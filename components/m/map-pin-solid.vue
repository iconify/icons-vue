<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuk4pobuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuk4pobuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-solid" /></template>
