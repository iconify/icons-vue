<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtwa-mbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rtwa-mbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:satellite-bold" /></template>
