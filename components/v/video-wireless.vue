<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btj3do1ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btj3do1ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-wireless" /></template>
