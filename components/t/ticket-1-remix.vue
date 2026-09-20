<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpa6e9sza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mpa6e9sza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ticket-1-remix" /></template>
