<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjwruuv3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjwruuv3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:telegram-fill" /></template>
