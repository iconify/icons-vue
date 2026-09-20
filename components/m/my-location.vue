<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyhdj7bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyhdj7bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:my-location" /></template>
