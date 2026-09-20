<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rczmumb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rczmumb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:upload-outline" /></template>
