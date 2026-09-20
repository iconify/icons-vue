<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svahi-bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svahi-bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:unraid" /></template>
