<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyr-ws_tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyr-ws_tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-pisces-round" /></template>
