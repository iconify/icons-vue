<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/limck8wdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="limck8wdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:production-belt-solid" /></template>
