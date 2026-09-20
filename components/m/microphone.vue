<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx9ziwb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx9ziwb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microphone" /></template>
