<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldr7rolws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ldr7rolws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spray-paint-remix" /></template>
