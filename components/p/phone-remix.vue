<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whlbo9qbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="whlbo9qbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-remix" /></template>
