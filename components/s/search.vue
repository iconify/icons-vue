<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipwt-eb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ipwt-eb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:search" /></template>
