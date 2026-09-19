<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxu-7-bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="nxu-7-bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:notdef" /></template>
