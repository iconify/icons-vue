<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anks12bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anks12bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-text-sharp" /></template>
