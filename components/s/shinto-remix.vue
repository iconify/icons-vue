<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt4rnojpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt4rnojpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shinto-remix" /></template>
