<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0lbnv8ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0lbnv8ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vibration" /></template>
