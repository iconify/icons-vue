<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lndl7fqqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lndl7fqqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:robot-face-happy-sharp" /></template>
