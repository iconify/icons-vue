<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wosy2ac-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wosy2ac-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speedometer" /></template>
