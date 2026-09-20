<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ihcgbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h-ihcgbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wallet" /></template>
