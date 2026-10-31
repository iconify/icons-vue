<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swxnh4qgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swxnh4qgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-close-corner-fill-round" /></template>
