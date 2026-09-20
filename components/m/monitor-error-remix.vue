<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_-watkyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h_-watkyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:monitor-error-remix" /></template>
