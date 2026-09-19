<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3iokvjwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3iokvjwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:random" /></template>
