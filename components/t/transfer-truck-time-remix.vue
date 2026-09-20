<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwo_g8yno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iwo_g8yno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:transfer-truck-time-remix" /></template>
