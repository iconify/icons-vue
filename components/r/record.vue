<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjtd9c19h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mjtd9c19h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:record" /></template>
