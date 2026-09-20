<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhad4bb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhad4bb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:monitor-pause-line" /></template>
