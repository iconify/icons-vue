<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc2e3ggwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fc2e3ggwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:transfer-truck-time-remix" /></template>
