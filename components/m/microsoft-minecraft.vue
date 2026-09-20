<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxiyiuble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxiyiuble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-minecraft" /></template>
