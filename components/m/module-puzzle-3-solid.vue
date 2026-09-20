<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ns3z9pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q3ns3z9pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:module-puzzle-3-solid" /></template>
