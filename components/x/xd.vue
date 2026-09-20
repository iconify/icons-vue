<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru8hiep1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru8hiep1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:xd" /></template>
