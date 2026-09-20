<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpzw5abdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpzw5abdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-input-scart" /></template>
