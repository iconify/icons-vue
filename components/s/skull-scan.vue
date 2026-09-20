<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfc0jvbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfc0jvbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skull-scan" /></template>
