<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jat1igb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jat1igb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:no-filter-filled" /></template>
