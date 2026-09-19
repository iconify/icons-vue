<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9azydbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":480};
const content = `<path class="n9azydbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:network-off" /></template>
