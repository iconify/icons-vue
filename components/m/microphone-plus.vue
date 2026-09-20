<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha04nrbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha04nrbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microphone-plus" /></template>
