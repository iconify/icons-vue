<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykq_gph3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykq_gph3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:midi-port" /></template>
