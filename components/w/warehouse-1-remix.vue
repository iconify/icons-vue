<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx_ww2ygm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mx_ww2ygm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:warehouse-1-remix" /></template>
