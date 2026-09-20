<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9x15ko7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9x15ko7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:upload-sharp" /></template>
