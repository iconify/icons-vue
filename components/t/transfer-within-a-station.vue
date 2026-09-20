<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmvgrwz3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmvgrwz3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transfer-within-a-station" /></template>
