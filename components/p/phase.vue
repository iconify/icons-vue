<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woz_0rcvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="woz_0rcvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:phase" /></template>
