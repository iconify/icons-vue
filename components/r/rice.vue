<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnjvlvuwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wnjvlvuwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rice" /></template>
