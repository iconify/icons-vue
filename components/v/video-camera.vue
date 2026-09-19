<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_tg_kblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_tg_kblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:video-camera" /></template>
