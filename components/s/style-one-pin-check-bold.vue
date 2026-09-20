<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs4tugg8n.css';
import '../../css/s/si7tzgbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs4tugg8n"/><path class="si7tzgbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:style-one-pin-check-bold" /></template>
