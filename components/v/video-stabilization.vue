<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz0f1vbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz0f1vbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-stabilization" /></template>
