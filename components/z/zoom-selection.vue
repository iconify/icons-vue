<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipaqwylxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipaqwylxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:zoom-selection" /></template>
