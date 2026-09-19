<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_0mflbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="s_0mflbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:n-3-square" /></template>
