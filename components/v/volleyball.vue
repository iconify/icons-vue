<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5_0g-2pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5_0g-2pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:volleyball" /></template>
