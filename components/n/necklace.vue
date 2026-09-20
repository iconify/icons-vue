<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax89p-b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax89p-b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:necklace" /></template>
