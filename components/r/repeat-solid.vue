<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in4ubz10s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in4ubz10s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:repeat-solid" /></template>
