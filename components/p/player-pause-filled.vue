<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e06y5c2ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e06y5c2ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-pause-filled" /></template>
