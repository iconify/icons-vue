<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veh0-ibhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="veh0-ibhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:subtract-1-remix" /></template>
