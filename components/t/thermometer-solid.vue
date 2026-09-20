<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkr-217ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wkr-217ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:thermometer-solid" /></template>
