<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha14l_bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ha14l_bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:thermometer-remix" /></template>
