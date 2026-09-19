<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p823y6bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p823y6bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:square" /></template>
