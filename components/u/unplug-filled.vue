<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga25rfbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga25rfbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:unplug-filled" /></template>
