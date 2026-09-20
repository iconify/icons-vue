<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r20rynojt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r20rynojt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:task-auto" /></template>
