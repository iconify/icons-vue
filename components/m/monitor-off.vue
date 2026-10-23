<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thqlobbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thqlobbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:monitor-off" /></template>
