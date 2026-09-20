<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onhg1w-oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="onhg1w-oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:syncwave-light" /></template>
